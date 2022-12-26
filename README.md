# SmartContractScanner-Action
Github Action for Scanning for Smart Contract vulnerabilities



This action will run on every push to the repository, and will use the Mythril tool to scan the contract.sol file for common vulnerabilities. If any vulnerabilities are found, it will send an email to the repository maintainer using the MailGun API and send a message to a Discord channel using the Discord API.

You will need to replace the placeholder values in this action with your own MailGun and Discord API keys and other details. You can also modify the action to fit your specific needs, such as by using a different tool or service to scan the smart contract or by sending the alert to a different email address or Discord chann
