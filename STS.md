is used by the get-account-number.js file
which has the function getAccountNumber
which uses the sts.getCallerIdentity() method
which is called by getAccountNumberRace
get-account-number.js file exports the getAccountNumberRace as getAccountNumber
The getAccountNumber method is then used in the cache sub-module in the cache.js file
