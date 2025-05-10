## Project Description
Telegram Bot API Manual Testing with Postman
This project includes a full suite of manual API test cases for the Telegram Bot API using Postman, focusing on both common and uncommon endpoints such as message sending, editing, retrieving chat details, and managing chat permissions.

 ## Project Overview
Manual testing for Telegram Bot API using Postman

Covers required/optional parameters, error handling, and negative testing

Organized test cases based on API categories (Messages, Chat, Admin, etc.)

Supports quick validation of Telegram bot behavior and integration logic
## Project Demo
https://drive.google.com/file/d/14KIxVTIDEc7oaNGVY3QnjpYon53ReZZC/view?usp=sharing

## Repository Structure

├── Postman_Collections/
│   └── TelegramBotAPI.postman_collection.json
├── Postman_Environment/
│   └── TelegramBotEnvironment.postman_environment.json
├── TestCases/
│   └── TelegramBotAPITestCases.xlsx
├── Screenshots
│   └── (HTML report)
└── README.md
- What’s Covered
sendMessage, editMessageText, getChat, getChatMemberCount

setChatPermissions, restrictChatMember, etc.

Status code checks, response time, and response body structure

Negative testing for invalid/missing parameters

## How to Use
Import the Postman collection and environment into Postman.

Set your bot token as an environment variable:
bot_token = YOUR_BOT_TOKEN

Use the defined test scripts or manually send requests and observe responses.

Refer to the Excel file for test case IDs, descriptions, expected results, and actual results.

## Test Case Documentation
Test cases are organized and documented in an Excel file with:

Test ID

API Endpoint

Scenario Description

Input Data

Expected Result

Actual Result

Status (Pass/Fail)



 ## Notes
Make sure your bot is active and allowed to message the target chat or user.

API base URL used:
https://api.telegram.org/bot{{bot_token}}/METHOD_NAME

