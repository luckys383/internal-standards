1. [LA-01](#la-01) No sensitive information should be present anywhere except .env files
1. LA-02 Env variables should never be used using env() function directly anywhere except config files
1. LA-03 Don't add new config keys in standard Laravel Or Package fiiles. Create new config files custom config needs.
1. LA-04 .env.sample should contains all keys that needs be added in .env file. With sensible default or placeholders
1. LA-05 Only use stable releases of composer packages
1. LA-06 Dont use wild card for pakcage version which allow auto upgrade to major release
1. LA-07 Use Eager loading alleviates the N + 1 query problem.
1. LA-08 Avoid calculation/logic operations inside the view layer.
1. LA-09 Always use Request Classes for performating validation on request Data unless it's 1-2 rule validation only.
1. LA-10 Facade are be used only in View/Controllers/Validation/Route layers. Use direct classed at all other places
1. LA-11 All atomic database operations which are supposed to run or fail as a whole should be wrapped in DB Transactions
1. LA-12 Always Use Queues for sending emails
1. LA-13 Always use migrations for all database schema related operations. No direct change should be made
1. LA-14 All migrations should have appropriate down function implementation
1. LA-15 Changes to old migrations are not allowed. Always create new ones.
1. LA-16 All data fileds should be added in models $data array property for casting
1. LA-17 Never use php date and datetime libraries. Always use Carbon
1. LA-18 Enable concurrency check on resource editing - only for predefined resources
1. LA-19 Private files should not be available publicly
1. LA-20 Always store dates/datetimes in UTC.
1. LA-21 Always store dates in UTC.
1. LA-22 For Json Response All Resources should be passed through a transformer layer.
1. LA-23 CSRF protection should be enabled for all forms.


## LA-01
We should never include any sensitive information like password, access_tokens, username, payment details etc in project files. And hence should never
be committed to the git. They should only be added in the .env file.




