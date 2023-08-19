# Card Management Service

### Role
Handles card-related information.

### Description
- **Tokenization**: Converts sensitive card information into secure tokens, reducing PCI-DSS scope.
- **Card Storage**: Securely stores tokenized card details in MySQL, ensuring encryption at rest.
- **Card Verification**: Implements card validation checks to ensure provided card details are valid.
- **Expiry Monitoring**: Notifies users when saved cards are nearing their expiration date.
