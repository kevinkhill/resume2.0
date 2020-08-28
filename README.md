# Kevin Hill - Programmer

# Education

### Sierra College, Rocklin CA | AA Computer Science

**2002 - 2006** | Rocklin High School Graduate  
**2006 - 2009** | General Education & Programming; C, Bash, Java, HTML, and PHP

# Job History

### Harris & Bruno | Journeyman Machinist, CNC Programmer

**2006 - Present** | Extensive range of responsibilties over the years

- Mastercam version migrations across multiple PCs
- Managing our program vault and creating a set of standards for using it [1]
- I was tasked with tooling, fixturing, and programming a brand new machine installation.
- Created an extensive spreadsheet tracking all the programs and tooling for a pair of CNC machines.
- Created an "app" out of a Google Sheet (wrote some additional scripts) for my supervisor to assign programming tasks and track completeness.
- Given admin passwords and server room access in case our sole IT provider is away.
- Dozens of other scripts, tools, sites, apps and such to ease my job.

<br/>

# Software & Languages

**Learned Formally**: HTML, CSS, PHP, SQL, Java, C  
**Self Taught**: Typescript/Javascript, NodeJs, Python, Shell Script, AutoIt, Lua

### Software

- Graphical
  - Mastercam (10+ years)
  - Excel / Spreadsheet software
  - VS Code
  - PHP Storm
  - Windows automation with AutoIt and StrokesPlus.net
- Command Line
  - Wrote my own version of a dotfiles manager for zsh that uses zplug for exensions
  - using just basic utils (find, grep, xargs) was able to solve this question for my coworkers "Is there a way we can search all our programs, to figure out if any still use T15"

<br/>

# OpenSource Projects

### Lavacharts - PHP Charting library powered by the Google Chart API

**Repo**: https://github.com/kevinkhill/lavacharts  
**Website**: [lavacharts.com](http://lavacharts.com)  
**Stats**: [646K+ packagist installs](https://packagist.org/packages/khill/lavacharts), [1,300+ commits](https://github.com/kevinkhill/lavacharts/commits/3.1), [used by 1K+](https://github.com/kevinkhill/lavacharts/network/dependents?package_id=UGFja2FnZS01NDI1Nzc2NjY%3D), [576 stars](https://github.com/kevinkhill/lavacharts/stargazers), [62 releases](https://github.com/kevinkhill/lavacharts/releases), and [18 contributors](https://github.com/kevinkhill/lavacharts/graphs/contributors)
**Tech**: PHP, JS  
**Description**: PHP Library for composing charts, serverside, and having the charts rendered in the browser with the Google Chart API  
**Summary**: I have been developing Lavacharts for close to a decade now, with an active user base and many contributors. It evolved from a need to have charts in a website I was making. It initially was a CodeIgniter package, then a Laravel package, and a Composer package. It used to string concat javscript together, then real javascript files, then Typescript! I have had so much fun and learned so much from maintaining this project.

### LavaJs - A simple wrapper for the Google Chart API

**Repo**: https://github.com/lavacharts/lava.js  
**Website**: [Github Pages](https://lavacharts.github.io/lava.js/)  
**Tech**: Typescript  
**Description**: PHP Library for composing charts, serverside, and having the charts rendered in the browser with the Google Chart API  
**Summary**: This is a port of the internals of Lavacharts into it's own package that could be used with any project. I almost got it off the ground before my daughter was born, so I didn't feel confident "releasing" it if I couldn't support it. It is completely useable, just not officially set free.

### PhpDuration - Converting / Storing durations of time

**Repo**: https://github.com/kevinkhill/php-duration/  
**Stats**: [211K+ packagist installs](https://packagist.org/packages/khill/php-duration), [125 stars](https://github.com/kevinkhill/php-duration/stargazers), and [7 contributors](https://github.com/kevinkhill/php-duration/graphs/contributors)  
**Tech**: PHP  
**Description**: Created for Harris & Bruno to use in the setup sheet website, for storing and representing program runtimes. Later released as an open source project since I couldn’t find a good library elsewhere. It has filled a niche with 127,000+ downloads, almost 100 starts, and 6 other users contributing code and bug fixes.

### FontAwesomePHP - A PHP library for Font Awesome Icons

**Website**: https://kevinkhill.github.io/FontAwesomePHP  
**Repo**: https://github.com/kevinkhill/FontAwesomePHP  
**Tech**: PHP  
**Description**: Another personal project, but released later to the public because I found it useful. While smaller than Lavacharts, 24k+ people have found it useful enough to download it.

<br/>

# Freelance Projects

### Mastersingers

**Website**: [mastersingers.org](http://mastersingers.org)  
**Tech**: [Bolt CMS](https://bolt.cm/)  
This was a freelance project to redesign the website of a local professional singing group. We paired up to help build my portfolio of work while developing them a new website on a moderade budget.

<br/>

# Work Projects

### Post Processor Design

**Description**: A post processor takes generated NCI info from Mastercam and runs it through the "post" to generate NC code.  
**Summary**: Generic posts come with the software but I have made dozen of improvements to ours, tailored for our workplace. One feature I am proud of is the extraction and generation of axis positions from the 3D models of the parts. This allows the operator to completely skip a time consuming step. Win! (All self-taught because Mastercam resellers want you to buy their posts) Another money saving feature is statically written probing cycles, masquerading as custom drill cycles. This allows me to use the Mastercam interface to output custom probing cycles, without having to buy the ProductivityPlus probing package.

### ShaggysLittleHelper | [Repo]()

**Tech**: AutoIt  
**Description**: A utility app that simplifies and automates multiple aspects of my workflow and Mastercam programming. It runs in the tray providing hotkeys, tasks shortcuts and scripted click-throughs. I use it every day and add features when I need.

### Serial Sender | [Repo]()

**Tech**: NodeJs, Express, serial port communications  
**Description**: A SPA that runs off an underlying express server. It simply provides a search interface for the programs, then uses a serial package to transmit the file into the CNC machine. It was born from the need to quit using floppy disks to transfer files and avoid paying any fees for software to do simple serial transmission.

### Setupsheets Web App | [Repo](https://gitlab.com/harris-bruno/setupsheets)

**Website**: [hbcnc.shop](http://hbcnc.shop)  
**Tech**: PHP, Laravel, Bootstrap, OwnCloud  
**Services**: DigitalOcean, Google oAuth, Algolia  
**Summary**: My coworkers had different ways of managing setup sheets for workcenters; It varied between no setupsheets up to a massive excel document with dozens of tabs. I created that we could all use, a central repo for all our setupsheets. Using Laravel and Bootstrap, I made a site to create setups, upload photos, add notes, group by workcenter, search. It uses our gSuite accounts to login and tracks all edits by user for accountability.  
**Additional Info**: After a few months, users didn't enjoy the photo upload process so I setup OwnCloud on our VPS and integrated the file store into my app. This provided seamless syncing of photos to the site using the OwnCloud desktop app on the workcenter PCs.

### Inventory Web App | [Repo](https://gitlab.com/harris-bruno/405-inventory)

**Website**: [inventory.hbcnc.shop](http://inventory.hbcnc.shop)  
**Tech**: PHP, Laravel, Bootstrap  
**Services**: DigitalOcean, Google oAuth, Algolia  
**Description**: Website application for tracking component inventory, monitoring levels, re-ordering, and email alerts.  
**Summary**: We had a new cnc machine installed and I was tasked with tooling up the machine. I wanted to keep an inventory of all the drill, tap, endmills, etc. Initially I had a detailed Google Sheet, but I later used the framework from the setupsheet app to create a similiar app. Included was an implementation of a shopping cart so I could "re-order" my own inventory. (It just sent off a nicely formated email to purchasing with part numbers and links to make it as easy as possible for them to get me what I need.)

### GEMBA App | [Repo](https://gitlab.com/harris-bruno/gemba-app)

**Tech**: Typescript, Monorepo, NodeJs, Vue, Vuetify  
**Description**: Report Aggregator with stats calculation and charts.  
**Summary**: Born from the depths of my frustration with an admin task, I have been working on an app to reduce a daily task to fully automatic.  
**Problem**: Every day we have OnePoint generate a report for the employees that worked and NetSuite generates a report of all the jobs completed and hours, etc. Each day someone takes both reports, and inputs the data into a third spread sheet to calculate some more values. One of the reports is also manually pivoted and printed to be distributed to each workcenter.  
**Solution**: I have been working on a site, with integrated processors for the reports. So far I have completed both report processors, a department service for normalizing the names between the two. An "UPEH" service, which calculates the required data from the two reports. This serivce powers a CLI tool that I use to manage processing the reports and creating bundles of the output. I took inspiration from eslint and webpack, using clipanion (powers yarn!) The service also power a Vue app that will handle uploading of reports and displaying the charts and tables.

### CNC Assistant | [Repo](https://gitlab.com/harris-bruno/cnc-assistant)

**Tech**: NodeJs, NW.js, Vue, Vuetify  
**Description**: Desktop application with many different modules to help my fellow coworkers with their daily jobs.
**Summary**: This was always an ambition of mine, to make a desktop app. It currently can read a directory of NC files (Program Vault we call it) and extracts photos, markdown files, and notes. All setup information can be co-located with the programs and therfore, eliminate all the overhead of file syncing and uploading to a webapp. I have many other feature ideas for the app, but it is currently stalled because I started a different project to overcome problem.

### Fastems Bridge | [Repo](https://gitlab.com/harris-bruno/fastems-bridge)

**Tech**: MS Access, Python, Fastems, SOAP services  
**Description**: Automation bridge for creating Fastems WorkOrders based off an exported MS Access schedule.  
**Summary**: For every job that showed up on my schedule, I would have to use the Fastems web interface (Silverlight based) to create a new WorkOrder. We needed a way to keep them both in sync, and up to date, to get accurate projections and parts done on time.  
**Process**:

- Network monitoring and request capturing to figure out the shape of the requests.
- Write SOAP service in python to masquerade as the Fastems webapp and make requests.
- Write python services to read, parse, and craft compatible payloads to send to Fastems via new SOAP service.
- Link both services to fully automate
- Profit!

### RenPy | [Repo](http://gitlab.com/harris-bruno/renpy)

**Tech**: Python, Fanuc Macro B  
**Description**: RenPy (Renishaw + Python) is a modified version of NC code with accompanying interpreter that is used for aiding in the writing of Macro NC files.  
**Summary**: I needed a way to write macro program while keeping track of many different variable. The old guys would write on paper `#543, tap depth` or the like. I wrote an interpreter than takes in my new file type `.renpy` and outputs `.NC` files. It can name variables and have them translated to their corresponding macro #s when ran through the RenPy interpreter. The resulting output is a valid, runnable NC file. It is a glorified global regex replacer to do something akin to `/#DRILL_DEPTH/#543/g` which was defined in the header and stripped when parsed. I still would like to implement the NC Parser I made to be able to virtually "run" the macro programs, and debug the variables. This would be huge since we wouldn't have to use an actual machine panel to run and debug macro programs!

### Better Schedule | [Gitlab Repo](https://gitlab.com/harris-bruno/better-schedule)

**Tech**: PHP
**Description**: PHP WebUI for an Access Database Report.  
**Summary**: Our old schedule for workcenters was based off MS Access. The problem was that nothing was grouped, or sorted, and it was hard to decipher what to do each day (The person who made it was not great at it). I created an app that would read a csv exported version of the report and manipulate it for clarity. Grouping by due date, sorting by due date, colorizing day of the week, hours planned summary. Even icons for if a job was running, not running, programmed or not.

### G84 Checker | [Gitlab Repo](https://gitlab.com/harris-bruno/g84-checker)

**Tech**: Python  
**Description**: Small utility program that scans an NC file for any taps that are not using G84. It can be used from the command line, when given a path to an NC file.  
**Summary**: Our old tool libraries had tools with the wrong cycle code applied. When posting from Mastercam, a tap could end up with a `G81` which will break the tap. This little tool searches for tool comments with `TAP` in the name and assumes a `G84` should be present. If not, it returned the result and we then alert the programmer that they might be breaking a tool. Save me quite a few times.

### Program Number Checker | [Gitlab Repo](https://gitlab.com/harris-bruno/program-number-checker)

**Tech**: Python  
**Description**: Small utility program that scans a directory of NC files, searching for any that contain the same program number as to one given.  
**Summary**: The FASTEMS system our machines are attached to uses NC porgram numbers as IDs for jobs. If I post, say, `HB123` as `O123`, then also post `HB456` as `O123`, it would overwrite. I needed a way to help safe-guard against this, so I used the same framework as the G84-checker to implement a similiar tool to run after posting.

### XShaft Generator | [Repo](https://gitlab.com/harris-bruno/xshaft-generator)

**Tech**: HTML, JS, Python, Bootstrap, Knockout.js  
**Summary**: This was made to simplify the programming of common part families. It had similiar features with adjustable locations. Included was a cgi module that could save the generated code out to a flash drive through the app.

### Botman | [Repo](https://gitlab.com/harris-bruno/botman)

**Tech**: PHP  
**Summary**: Exploration of creating a Slack chatbot to interact with some services on my local PC

---

## Personal Projects

This section is about all my pet projects, that relate to code in some form or another. Things I have made for fun or as experiments.

### NcStat | [Repo](https://gitlab.com/harris-bruno/ncstat)

**Tech**: Typescript, Vue  
**Description**: Static analyzer for NC files.  
**Summary**: Monorepo with the packages for my implementation of an NC parser. It can read simple Fanuc based NC files while tokenizing. There is a WebUI written in Vue as a demo for an application that could use the parser.

### TsTokenizr | [Repo](https://github.com/kevinkhill/ts-tokenizr)

**Tech**: Typescript, Vue  
**Description**: Static analyzer for NC files.  
**Summary**: Monorepo with the packages for my implementation of an NC parser. It can read simple Fanuc based NC files while tokenizing. There is a WebUI written in Vue as a demo for an application that could use the parser.

### TopDawg Sports | [Repo]()

**Tech**: NodeJs, nightmare.js  
**Summary**: My friend was manually copying information from web pages into a spreadsheet and asked if I could help automate the process. I wrote a recursive web scraper with node and nightmare that logged in and pulled 30k+ records from a few hundred pages in mere hours.

### Pi Lights | [Repo](https://github.com/kevinkhill/pi-lights)

**Tech**: Raspberry Pi, Python, Circuitry  
**Summary**: I built a relay module with an outlet so I could plug my christmas tree into it. I then made a python webui dashboard to control the outlet from my phone. Bonus feature was downloading a midi file of Metallica's "For Whom the Bell Tolls" and syncing the relay to the kick drum.

### Pi Garage Door

**Tech**: Raspberry Pi, Python, Circuitry  
**Summary**: Using a magnetic reed switch, setting up a sensor for a garage door that can notify the status to a webapp. I also took apart an old opener and hooked it to the GPIO of the pi to enable web based remote control!

### Xbox Modding

**Tech**: Xbox, Hardward  
**Summary**: Swapping the hard drive for a 1TB in the original Xbox. Then softmodding and installing XBMC (what is now KODI). Playing Super Mario World, through an emulator, on an Xbox was quite an accomplishment.

### Phone Rooting

**Tech**: Android  
**Summary**: I have rooted and installed custom roms on most of my phones.

### Ikariam | [Repo](https://github.com/kevinkhill/ikariam)

**Tech**: Javascript  
**Summary**: I wrote a few mods and extensions for the online game Ikariam.

### FsNode | [Repo](https://github.com/kevinkhill/fs-node)

**Tech**: Typescript  
**Summary**: Playing around with functional programming and typescript while making a useful package for traversing the file system.

### dpkg-github | [Repo](https://github.com/kevinkhill/dpkg-github)

**Tech**: Shell  
**Summary**: For fun and for a challenge, I wrote this on my phone over ssh. It is just a simple utility script for installing binaries found on github with dpkg.

### Join API | [Repo](https://github.com/kevinkhill/join-api)

**Tech**: Node, Javascript  
**Summary**: Node library for using the Join API (a similiar service as PushBullet, made by the creator of Tasker)

### CEMD | [Repo](https://github.com/kevinkhill/cemd)

**Tech**: PHP, Javascript, Bootstrap
**Summary**: I needed a webui to manage permissions for the Setup Sheets app and at the time, there wasn't one. I made this but never really finished it as I ended up ditching the system.
