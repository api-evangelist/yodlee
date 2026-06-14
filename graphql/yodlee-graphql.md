# Yodlee GraphQL Schema

## Overview

This document describes a conceptual GraphQL schema for the Yodlee (Envestnet | Yodlee) financial data aggregation platform. Yodlee exposes its capabilities through a REST API (Core APIs v1.1), and this schema represents a GraphQL translation of those capabilities covering account aggregation, transaction enrichment, holdings, providers, documents, statements, budgets, net worth, and derived analytics.

## Source

- Provider: Yodlee (Envestnet | Yodlee)
- API Style: REST (Core APIs v1.1)
- Base URL: https://production.api.yodlee.com/ysl
- Developer Portal: https://developer.yodlee.com/
- Documentation: https://developer.yodlee.com/resources/yodlee/yodlee-api-overview/docs/overview
- GitHub: https://github.com/Yodlee

## Schema Source

This is a conceptual schema derived from the Yodlee REST API surface. It is not an officially published GraphQL endpoint by Yodlee/Envestnet.

## Key Domains

### User Management
Types covering registered users, user preferences, and user profile details including locale, currency, timezone, and time zone settings.

### Account Aggregation
Types for financial accounts (bank, credit, investment, insurance, loan), account balances, account profiles (ownership, address, holder info), and container-level categorization.

### Provider Management
Types for financial institutions (providers), provider accounts (linked accounts per user), login forms, credential fields, field choices, and related configuration.

### Transactions
Types for individual financial transactions, transaction categories (system and custom), transaction filters, and transaction request parameters.

### Statements
Types for account statements, credit and debit line items within statements.

### Holdings and Investments
Types for investment holdings, asset classifications, investment plans, and insurance policies.

### Documents
Types for financial documents (tax forms, statements) associated with accounts.

### Derived Analytics
Types for aggregated derived data including net worth summaries, cash flow analysis, asset and liability summaries, transaction-level aggregations, and allocation summaries.

### Payments
Types for bill payment methods and payment detail records.

### Budgets
Types for user-defined budgets, budget categories, and budget periods.

### Access and Auth
Types for access tokens and access token requests used in API authentication flows.

## Type Summary

| Domain | Types |
|---|---|
| User | User, UserDetail, UserPreference |
| Account | Account, AccountProfile, AccountBalance, Container |
| Provider | Provider, ProviderAccount, ProviderAccountPreference, ProviderDetail |
| Credentials | UserCredential, LoginForm, FormField, FieldChoice, FieldRelativeField |
| Transaction | Transaction, TransactionCategory, TransactionRequest, TransactionFilter |
| Statement | Statement, StatementCredit, StatementDebit |
| Holding | Holding, AssetClassification |
| Site | SiteAccount, Login, LoginProfile |
| Access | AccessToken, AccessTokenRequest |
| Document | Document, TaxStatus |
| Payment | BillPayment, PaymentMethod, PaymentDetail |
| Budget | Budget, BudgetCategory, BudgetPeriod |
| Money | MoneyData |
| Derived | DerivedTransaction, DerivedAccount, NetworthSummary, AllocationSummary, CashFlow, AssetSummary, LiabilitySummary |
| Investment | Investment, InvestmentPlan, InsurancePolicy |

## GraphQL Schema File

See `yodlee-schema.graphql` for the full type definitions.
