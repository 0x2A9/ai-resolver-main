# AI Resolver Main
The **main** component of the **AI Resolver** project. Contains web application, which connects **UI** with the **AI Microservice** component that solves sudoku. The current component also contains predefined sudoku solving algorithm 

# Set Up
- To use the **Docker** instead of manual installation follow the ```ai-resolver-docker``` repository setup
- The next packages should be enabled to install: 
   - ```php-curl```
   - ```php-xml```
   - ```php-mbstring```
   - ```php-intl```
   - ```php-common```
   - ```php-mongodb```
- Create and configure ```.env``` file
- Run the following commands from the repository root:
	```bash
	npm ci
	𝚌𝚘𝚖𝚙𝚘𝚜𝚎𝚛 𝚒𝚗𝚜𝚝𝚊𝚕𝚕
	𝚌𝚘𝚖𝚙𝚘𝚜𝚎𝚛 𝚍𝚞𝚖𝚙-𝚊𝚞𝚝𝚘𝚕𝚘𝚊𝚍 -𝚘
	𝚙𝚑𝚙 𝚊𝚛𝚝𝚒𝚜𝚊𝚗 𝚖𝚒𝚐𝚛𝚊𝚝𝚎
	```
- For the first **DB** seeding:
	```bash
	𝚙𝚑𝚙 𝚊𝚛𝚝𝚒𝚜𝚊𝚗 𝚍𝚋:𝚜𝚎𝚎d
	```
- Refreshing **DB**:
	```bash
	𝚙𝚑𝚙 𝚊𝚛𝚝𝚒𝚜𝚊𝚗 𝚖𝚒𝚐𝚛𝚊𝚝𝚎:𝚏𝚛𝚎𝚜𝚑 --𝚜𝚎𝚎𝚍
	```
- Add project hosts to ```/𝚎𝚝𝚌/𝚑𝚘𝚜𝚝𝚜```:
	```
	127.0.0.1     ai-resolver-main
	127.0.0.1     ai-resolver-mind-ms
	```
- Set **Prettier** as the default formatter in the **IDE** ```settings.json```:
	```json
	{
		"𝚎𝚍𝚒𝚝𝚘𝚛.𝚍𝚎𝚏𝚊𝚞𝚕𝚝𝙵𝚘𝚛𝚖𝚊𝚝𝚝𝚎𝚛": "𝚎𝚜𝚋𝚎𝚗𝚙.𝚙𝚛𝚎𝚝𝚝𝚒𝚎𝚛-𝚟𝚜𝚌𝚘𝚍𝚎",  
		"𝚎𝚍𝚒𝚝𝚘𝚛.𝚏𝚘𝚛𝚖𝚊𝚝𝙾𝚗𝚂𝚊𝚟𝚎": true
	}
	```