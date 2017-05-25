# ym-product-uploader
Grunt task for automatically uploading a spreadsheet of store products to YourMembership

(c) TBS, 2017.  Open sourced under the MIT license (see LICENSE).

## Purpose
A utility program designed to be run locally (think, on your PC), which will read through a spreadsheet of store products and upload some or all of them to one or more instances of YM.  **Why?**  Because sometimes life is too short to type all your products in manually to YM, especially if:
* You have your store products in some other database anyway, and/or
* You have multiple instances of YM and need to have some or all of the same products in each instance, and/or
* You have multiple member pricing of products and calculate these using some formula, and/or
* You need to change a large number of store products relatively quickly.
We developed this utility because all of the above apply to our organization.

## Installation
The program should run on Windows, Linux and Mac machines, but has only be tested/used on Windows.

In order to make use of this program, you will first of all need to:
1. Download and install **node.js** from https://nodejs.org/
2. Install the **grunt cli** from here: https://gruntjs.com/
3. Clone this repo down to your machine (hint - check out the green button above)
4. Then open a node command line window and change to the folder where you have cloned this repo
5. Type
...
npm install
...

## Configuration
If you have managed to successfully complete all the Installation steps, then you should be ready to configure the program to work with your data and YM instances.  

## Running
...
grunt
...
Will run the program in test mode

...
grunt [--start=nn] [--stop=nn] [--target=XXXX] [--force]
...

**Examples**

