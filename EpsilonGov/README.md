This is a project collaborated by BetaGOV and some cool kids at CUSP




Data Preprocessing:

Here is some fact about the dataset: 



- DA case status: NOT A HELPFUL FIELD. Exclude.

- Exclude the following Codes in Summary Charge Statute # (equivalent column to Summary charge desc)
973.076(2)(a) 
343.44(1)(b)&(2)(ar)2
976.03

- Drop last year. Try to use Charge status and/or Charge dispo as proxies.

- Use Referral Type instead of Arrest status  (but try to see how do they match)