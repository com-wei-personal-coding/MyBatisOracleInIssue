# MyBatisOracleInIssue
resolution of  mybatis Dynamic sql in oracle db  in set  maxsize can not  over 1000
Judge   number of "criterion.listValue"  in  mybatis generated  file  *dao.xml
and Replace   the "criterion.listValue" with ognl expression version
the expression can Judge the criterion is "not in" or  "in"
if the criterion is not in ,the condition not in set a == not in a1 and not in set a2 ...and not in set an
if the criterion is in ,the condition   in set a ==   in a1 or   in set a2 ...or   in set an
    
    
   
