# Uwezo-fund-dataset
A new credit scoring  dataset with 1131 instances and 12 attributes created from data collected from Uwezo Fund loan and repayment submission reports in Emurua Dikirr, Kilgoris, Narok North and Sotik Sub-counties, Kenya for the period between 2014 and 2023. 
The dataset classifies groups described by a set of attributes as high and low scores.
Dataset characteristics: Multivariate
Subject area: social science
Associated Task:Classification
Feature type: Categorical, integer and date-type
Instances : 1131
Features: 12
Has a number of missing values
variables
Attribute	Explanation	Datatype
SNo.:	The number of the group as captured in excel	int64
Name of the group/institution"	the name of the group or institution	string
Sector:	The group’s activity or the purpose for the loan either agriculture, manufacturing, trade and service.	object
Amount Approved:	The amount applied by the group. Might be equal or less the amount issued	float64
Payment Voucher:	This feature has a number captured from the
Treasury authorizing payment to groups. For in- stance, payment voucher 100 was used to pay a specified number of groups. This feature is used by Uwezo for reconciliation and audit purposes. It is not part of the loan documents however is always captured.	object
Cheque No:	This feature is issued by the treasury for office consumption.	float64
Amount Issued:	Actual monetary value of the loan in Kenya
Shillings	float64
Remarks:	This represents the group’s recommendation from the officer in charge. It indicates the reason for the variance between amount approved and amount issued.	object
Date of Disbursement:	The date which loan was issued to a group	object
G.F.S.CODE:	The unique number based on county, sub-county, Sector and category	object
Category:	The presents   the   composition   of   the group/membership profile such as women if the members consist of 70 percent women, Persons with disability (PWDs) if the members consist of 70 percent PWDs and Youth consist of 70 percent youth.	object
Amount Due: The amount not yet paid. Determined by dividing the amount issued by twenty four and multiply- ing the result by the number of months elapsed since expiry of grace period.	float64
Amount repaid:The amount already repaid by the group	float64
Amount cumulatively in arrears:	The difference between amount due and amount repaid.	float64
Outstanding Loan Balance:The difference between amount issued and amount repaid.	float64

