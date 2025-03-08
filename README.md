The code enables you to convert soql code to apex, please make sure the SOQL query is correct.

Query example:

select id,IP_Active__c,IP_Question__r.IP_Active__c,IP_Question__r.IP_Required__c,IP_Answer__c,IP_AnswerPicklist__c,IP_Answer_LongText__c,IP_Investment__r.IP_Investment_Status__c,IP_Investment__c from IP_Investment_Response__c where IP_Investment__c = :investmentId
