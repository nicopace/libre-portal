# Libre Mesh Community Portal

Includes code for [pitbull](https://github.com/libremesh/pitbull), [lime-packages-ui/lime-voucher](https://github.com/libremesh/lime-packages-ui).

## Usage
Make sure you have NodeJS installed and a LibreMesh router accessible thru `10.5.0.1`.

`git clone https://github.com/luandro/libre-portal.git`

Enter the directory and install dependencies for the app:
`cd libre-portal && npm run install`

Copy the necessary files to the router:
`npm run build-router`

Now you'll need to SSH into the router and run `service rpcd restart` on the router in order to restart ubus.

In order to start the application run `npm run start`. To create a new voucher login with the router's admin password.