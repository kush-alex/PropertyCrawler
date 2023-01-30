# PropertyCrawler
## Run app:
> npm run start
> npm run loadData

## Setup:
1. Configure local env
* npm init
* npm install --save express  
* npm install --save cors 
* npm install --save dotenv
* npm install --save aws-sdk 
* npm install axios cheerio
2. Install AWS CLI 
3. Configure AWS CLI
* api % aws configure
* AWS Access Key ID [None]: ****************
* AWS Secret Access Key [None]: **************
* Default region name [None]: eu-west-2
* Default output format [None]: json
4. Create table 
* aws dynamodb create-table --cli-input-json file://Property.json  --region eu-west-2