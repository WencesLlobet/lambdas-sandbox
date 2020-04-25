
## Goal: dynamodb counter 
	Timing: 18:18 - 18:40
	FAILED -> insit on it, boilerplate... 

## Goal: assert post in instagram with curl
	Timing: 18:45 - 19:00
	FAILED -> Cypress 

## Goal: assert mail received via curl
	Timing: 19:05 - 19:20	-> 19:44
	NOT FINNISHED 



# Spike 2

#Goal: assert new entry in database via aws cli
	Timing: 20:35 21:00 -- 

aws dynamodb query \
    --table-name Thread \
    --key-condition-expression "ForumName = :name" \
    --expression-attribute-values  '{":name":{"S":"Amazon DynamoDB"}}'

sortKeyName BETWEEN :sortkeyval1 AND :sortkeyval2 - true if the sort key value is greater than or equal to :sortkeyval1 , and less than or equal to :sortkeyval2 .

#Goal:  assert and decide Cypress/instagram API all in google search 
	Timing: 21:05 21:15
use the api !








- Enable the dynamo db stats service test



