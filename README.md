# Salesforce
1. Before insert records into a salesforce object (Trigger BeforeInsert),
   Do logical judgments, if not satisfied, throw out an error on front page. 
   + CloneOppHandler 
   + CloneOppHandler_Test
2. after the file is uploaded, change the name of file (Trigger AfterInsert),
   + RenameFileTrigger
3. when click button, js fires apex class to update the price of product
   + RefreshProductPrice
   + RefreshProductPrice_JS
