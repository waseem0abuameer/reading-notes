# Payment Processing


===============================================================================================================

## How to read Technical Documents as fast as possible
1. Establish why you are reading it
2. Get an overview of the content and structure of the document
3. Take 30s to 2 minutes to scan the rest of the document. Click on the scrollbar and just breeze through all the pages. Just look at the pictures, tables and diagrams. Look for things that look familiar and that you will understand immediately. APIs, schematics, flow charts, block diagrams. Read the captions under the pictures.
4. If you want, stop at the interesting parts and take a deeper look. Stop when it gets boring.
5. Look at the table of contents again. You'll have a deeper understanding of the document after you look again.
6. Choose what to read next based on interesting-ness or usefulness. If there's nothing useful, close the doc. You can say that you've read it from cover to cover. ;)

- At anytime, If what you're looking for is not there, close the document and read something else. You can establish this at step 2 onwards.
- Learn to practice reading AND comprehension. This is done not by reading from start to finish, but by scanning pages and looking for meaningful words.
- So thanks for reading. I hope this helps. Go out and create something!

===============================================================================================================

## How Credit Card Processing Works

### Who are the actors in a credit and debit card transactions?

- A cardholder :
 obtains a credit or debit card from an issuing bank, uses the account to pay for goods or services.
- A merchant :
is any type of business that accepts card payments in exchange for goods or services.
- A merchant bank :
establishes and maintains merchant accounts. Merchant banks allow merchants to accept deposits from credit and debit card payments.
- Payment :
processors are companies that process credit and debit card transactions. Payment processors connect merchants, merchant banks, card networks and others to make card payments possible.
- Issuing banks: 
are the banks, credit unions and other financial institutions that issue debit and credit cards to cardholders through the card associations.
- Card associations:
 include Visa, Mastercard, Discover and American Express. The card associations set interchange rates and qualification guidelines, and act as the arbiter between - issuing banks and acquiring banks among other vital functions.


 ### What does credit card processing look like in motion?
Credit card processing works in three distinct processes: 

1. Authorization
2. Settlement
3. Funding

Now let’s look at the credit card settlement and funding process. This part is essentially how the merchant gets paid from the credit cards they accept.

1. Merchants send batches of authorized transactions to their payment processor.
2. The payment processor passes transaction details to the card associations that communicate the appropriate debits with the issuing banks in their network.
3. The issuing bank charges the cardholder’s account for the amount of the transactions.
4. The issuing bank then transfers appropriate funds for the transactions to the merchant bank, minus interchange fees.
5. The merchant bank deposits funds into the merchant account.

===================================================================================

## How Does Online Credit Card Processing Work?
1. Payment Gateway
The Payment Gateway is responsible for sending the credit card to the appropriate Internet Merchant Account over secure online channels.  The approval or decline of the transaction, however, is actually performed by the Merchant Account.  It is helpful to think of the Gateway as a router that sends the credit card information to the appropriate account.  It is also responsible for fraud checking and maintaining reliable links with the merchants.

4. Your Application
- User enters credit card information into the application
- Credit card information is sent to the Payment Gateway via a secure channel
- The Payment Gateway routes the credit card to the appropriate Internet Merchant Account
- Internet Merchant Account connects to the Merchant Account for credit card processing.
- The result is passed back to the Gateway and then the application.
3. Validation, Refunds, and Settlement
If the customer’s credit card is declined you will usually see a general message such as “there was a problem processing your credit card.”  For security reasons, the online user will usually not see the specific reasons for the failure, such as a decline. (The reason for this is that too much information makes it easier for hackers to fake credit card transactions.) However, the management side of the Gateway and third-party applications may allow you to find out more specific reasons for the failure.
4. Fees!
Although we’ve worked through the key concepts of online credit card processing, we still have one last area of confusion, which are fees.  Admittedly, the number of fees can be quite confusing, but the general formula is usually straight forward.