# satoshibox-clone
Satoshibox.com / Satoshidisk - Clone


1- Unzip folder Files/ into your www/ root.  
2- Create new database and import Database/database.sql in it.  
3- Edit the configurations inside the file requires/sell.class.php    

> Only this lines:
-------------------
// Website  
private $fee_service = 3; // % you want take for each transaction  
private $title = "SatoshiBox Clone ~ Sell your files for bitcoins";  
private $urlsite = "http://www.example.com";  
private $secretfolder = "secretfolder";  
private $authorized_ext = array(".zip", ".rar"); // Authorized extensions to upload from users  
// Admin Panel  
private $admin_username = 'admin';  
private $admin_password = 'admin';  
// Database Connection
private $host = "";
private $user = "";
private $password = "";
private $database = "";
// JSON RPC Configs
// Go to /etc/bitcoin/bitcoin.conf and write the details here
private $json_username = "";
private $json_password = "";
private $json_port = "";
private $json_server = "";

// CoinPayment API
private $cp_public = "";
private $cp_private = "";

public $cp_merchant_id = "";
public $cp_ipn_secret = "";
public $cp_debug_email = "";

You have to create a coinpayments.net account, generate new API and merchant ID, set IPN password.

This is all ! Enjoy your new service online !

If you have any problem or want customized work, please contact us at: info@progweb.info.
