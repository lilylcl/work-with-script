# Work with Script

## Installation

1. Clone this repository to a local directory

		git@github.com:Tim-Cao/work-with-script.git

## Configuration

1. Run the following command at the root directory of local repository

		python3 initialization.py

1. Generate jira API Token

	1. Sign in https://liferay.atlassian.net/

	1. Click the cog icon > Atlassian account settings > Security > Create and manage API tokens

	1. Create API Token

	1. Save generated token in your local file as you will not be able to see this again.

1. Generate github API Token

	1. Sign in https://github.com/

	1. Personal Menu > Settings > Developer Settings > Personal access tokens > Tokens(classic)  > Generate new token

	1. Add a name > Leave expiration as default > Select the following scopes

		![image](https://github.com/Tim-Cao/work-with-script/assets/52661397/3478cd82-4e48-4306-99a1-fab363498b24)

		![image](https://github.com/Tim-Cao/work-with-script/assets/52661397/68c7945c-ef1c-47d6-a8ad-a14d7f5d8922)

	1. Generate token

	1. Save generated token in your local file as you will not be able to see this again.

 1. Add a `credentials-ext.properties` file under the root directory to overwrite the `credentials.properties`

## Launch the app

1. Run the following command at the root directory of local repository

		python3 script_app.py

## Features

1. Create a pull request and forward

	![create_pr_and_forward](https://github.com/Tim-Cao/work-with-script/assets/52661397/c5098644-371f-4f02-9cad-6db868dba901)

	See pull request [styles](https://liferay.atlassian.net/wiki/spaces/QA/pages/2194800714/Script+to+manual+forward+PR+to+Brian#Styles)

1. Forward a failure pull request to BrianChan

	![forward_failure_pull_request](https://github.com/Tim-Cao/work-with-script/assets/52661397/cb298653-f9ba-485a-982f-9a14d1dac260)

	See pull request [styles](https://liferay.atlassian.net/wiki/spaces/~292455967/pages/2421522433/Script+to+create+a+PR+with+only+Poshi+changes+to+team+repo+then+forward#Styles)

1. Create a test fix ticket based on a given case result

	![create_test_fix_ticket](https://github.com/Tim-Cao/work-with-script/assets/52661397/b69c0165-1a41-4625-a263-de77e5dba11e)

1. Write a comments template to a given jira ticket

	![write_comments](https://github.com/Tim-Cao/work-with-script/assets/52661397/21540135-1a63-4ddd-b873-3a79152438e5)

	See comments [styles](https://liferay.atlassian.net/wiki/spaces/~292455967/pages/2402025586/Ticket+description+and+comments+template+on+Jira+Software+Cloud#Comments)

1. Write a description template to a given jira ticket

	![write_description](https://github.com/Tim-Cao/work-with-script/assets/52661397/78f01d51-9de6-4ed9-b9e8-d7fac2513a5e)

	See description [styles](https://liferay.atlassian.net/wiki/spaces/~292455967/pages/2402025586/Ticket+description+and+comments+template+on+Jira+Software+Cloud#Description)
