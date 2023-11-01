# credit_card_fraud
Consists of 20 important and diverse metrics and 8000 records of transactions

20 fields include: <br /><br />
- Transaction Date and Time: The date and time when the transaction occurred. This information can be useful for detecting unusual transaction times. <br />
- Transaction Amount: The amount of the transaction, which can help identify unusual or high-value transactions. <br />
- Cardholder Name: The name of the cardholder for reference and matching with transaction details. <br />
- Card Number (Hashed or Encrypted): The hashed or encrypted version of the card number to ensure privacy and security. <br />
- Merchant Name: The name of the merchant where the transaction took place. This can help identify potentially fraudulent merchants.  <br />
- Merchant Category Code (MCC): A code that categorizes the type of merchant (e.g., restaurants, gas stations, online retailers). <br />
- Transaction Location (City or ZIP Code): The location where the transaction was made, which can be used to detect unusual geographic patterns. <br />
- Transaction Currency: The currency used for the transaction, which can help identify foreign or unusual transactions. <br />
- Card Type: The type of card used (e.g., Visa, MasterCard, American Express). <br />
- Card Expiration Date: The date when the card expires. <br />
- CVV Code (Hashed or Encrypted): The hashed or encrypted version of the card's CVV code. <br />
- Transaction Response Code: The code returned by the payment processor to indicate the transaction's status. <br />
- Transaction ID: A unique identifier for each transaction. <br />
- Fraud Flag or Label: A binary column indicating whether the transaction is fraudulent (1 for fraud, 0 for non-fraud). <br />
- Previous Transactions: Historical transaction data for the same card or cardholder. This can help identify unusual patterns. <br />
- Transaction Source: Where the transaction was initiated. <br />
- IP Address: The IP address associated with the transaction, which can help detect online fraud. <br />
- Device Information: Details about the device used for the transaction (e.g., browser, device type). <br />
- User Account Information: If applicable, information about the user's account or profile. <br />
- Transaction Notes: Any additional notes or comments related to the transaction. <br />
