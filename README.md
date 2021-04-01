# communicate_data_findings

Loan Data from Prosper

by Mohamed Maguid

Data Set in general

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The dataset contains so-called listings which either have been transformed to a loan or not. Partially funded loans are possible as well. My main overall interest might be why and who is becoming a so-called Prosper borrower and furthermore what is mainly influencing the interest rate. Interesting would be how the average Prosper rate is compared to the normal financial market.

What is the structure of your dataset?

Some Information about This Dataset can be found in my Google Drive link below.

(https://drive.google.com/file/d/1SnL9_i9fbUx2M2MYTxwZ5jyLbOeLvQAD/view?usp=sharing).

Bid Object: A Bid is created when a Lender wishes to lend money to a Borrower in response to a Listing the Borrower created to solicit Bids. Bids are created by specifying an Amount and a Minimum Rate in which the Lender wishes to receive should the Bid win the auction and become a Loan. The Minimum Rate remains private unless the Bid is Outbid by other Bids offering a lower Minimum Rate.
Category Object: A Category is collection of Groups which share a common interest or affiliation. Categories are created by the Prosper Team. Group Leaders can associate their Group with one or more categories as they relate to their group.
CreditProfile Object: A CreditProfile is a timestamped set of extended credit information for a Member. Row level display and publication of CreditProfile is explicitly forbidden.
Group Object: A Group is a collection of Members who share a common interest or affiliation. Groups are managed by Group Leaders who bring borrowers to Prosper, maintain the group's presence on the site, and collect and/or share Group Rewards. Borrowers who are members of a group often get better interest rates because Lenders tend to have more confidence in Borrowers that belong to trusted Groups.
Listing Object: A Listing is created by a Borrower to solicit bids by describing themselves and the reason they are looking to borrow money. If the Listing receives enough bids by Lenders to reach the Amount Requested, then after the Listing period ends it will become a Loan. A Borrower may only have one active listing at a particular moment in time.
Loan Object: A Loan is created when a Borrower has received enough Bids to meet the full amount of money that the Borrower requested in their Listing. The Borrower must then make payments on the Loan to keep its status current.
Loan Performance Object: A LoanPerformance is an event in a Loan History that causes a change in loan value. This table can be used to calculate roll rates. Row level display and publication of LoanPerformance is explicitly forbidden.
Marketplace Object: The Marketplace is a collection of metrics and statistics about the Prosper Marketplace. These metrics are calculated daily. Historical metrics are provided as well.
Member Object: A Member is a registered user of the Prosper Marketplace site. A Member may have one or multiple roles which determines which actions the Member is allowed to perform on the site.
What is/are the main feature(s) of interest in your dataset?

Based on my high level questions I think these are the main attributes:

Who is using Prosper? (basically, which individuals, which professions, which part of the country, financial situation)
Occupation
EmploymentStatus
IsBorrowerHomeowner
BorrowerState
Why is Prosper used? (Is it related to rates, fees, or faster processing time)
ListingCreationDate
LoanOriginationDate
ListingCategory
BorrowerAPR
BorrowerRate
ProsperRating
Term
LoanStatus
What is primarily influencing the interest rate? (is it related to scoring, income and history)
ProsperRating (Alpha)
ProsperScore
DebtToIncomeRatio
IncomeRange
MonthlyLoanPayment
Term
