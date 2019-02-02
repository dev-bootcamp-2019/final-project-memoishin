# final-project-memoishin

## About the Project

The project is an Online Market Place. In the online market place, admins can add/ remove shop owners. When an owner is removed, the balance which has not been withdrawed is sent to the owner's address and the stores for this owner will no longer be visible.

When a shop owner is added, they can add store fronts. Once a store front has been added, they can add products that will be on sale for the store front. The shop owner will also be able to delete a product. They can also change prices of products.

When a shopper visits the page, they can browse the listed stores and products. They have option to buy products. Once a product is bought, the funds will be sent from the shopper to the contract. The shop owner can withdraw the funds from the contract.


### Step 1

Run `npm install` in the project directory.

[Update]
The npm install in this directory should've installed open zeppelin but I agree there is no package.json and is causing error. It should work without "npm install" in the top level directory.

Can you please just get the Ownable.sol and SafeMath.sol files and include it in the contracts folder and change the import location for both in the smart contract.

Change directory into *client*.

Run `npm install` in this directory.

### Step 2

Start Ganache [I have used GUI version 1.2.2]

### Step 3

Change directory into the project directory.

Run `truffle compile` in the project directory.  

If you're using Windows, use `truffle.cmd` instead of `truffle`.

### Step 4

Migrate your smart contract(s) onto your blockchain instance.

Run `truffle migrate --reset` in the project directory

### Step 5

Run `npm run start`. This will open the project in the browser on `localhost:3000`

### Step 6

Ganache Account 0 will be the admin account by default. Import this account in Metamask or `Reset Account` if it already existed.

### Step 7

Refresh Page. You will see Admin features if Metamask Account selection is for the Admin Address. Otherwise, you will see the shop owner page. 

### Step 8

Select Admin Account in Metamask and refresh page. You will see options to add/remove store owner. Copy and address from Ganache and add here. Import this account in Metamask as well. After you have added the address and changed account in Metamask. You can refresh the page to view Shop Owner Features. You can add stores, add/remove/edit products. You can also see current balance or withdraw funds.

### Step 9 

Import Another account in Metamask and refresh page. You will see shopper page. The user will be able to browse stores/ products and buy products on sale.
