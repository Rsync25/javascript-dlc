# Lightning implemenations support

# LND 

Make sure you have the lnrpc and grpc packages installed in your project (npm install lnrpc grpc). Replace the placeholders 'YOUR_LND_HOST', 'PATH_TO_TLS_CERT_FILE', 'YOUR_CONTRACT_INFO', and 'YOUR_INPUT_BLINDING_KEY' with the appropriate values for your environment.

Note that you need to have a running LND node with gRPC enabled and the correct TLS certificate file (tls.cert) path to establish a connection. 

# LDK 

Please make sure to replace the placeholders 'YOUR_PROVIDER_URL', 'YOUR_CONTRACT_ADDRESS', 'YOUR_PRIVATE_KEY', and 'YOUR_ADDRESS' with the actual values relevant to your setup. Additionally, ensure that you have the required dependencies (bitcoin-js and ldk-node-js) installed for the code to work properly.

# Core Lightning 

Make sure you have the core-lightning package installed in your project (npm install core-lightning). Replace the placeholder 'YOUR_LIGHTNING_DIRECTORY' with the path to your Core Lightning data directory.

# Eclair 

Make sure you have the eclair package installed in your project (npm install eclair). Replace the placeholders 'YOUR_ECLAIR_API', 'YOUR_ECLAIR_API_KEY', and 'PATH_TO_TLS_CERT_FILE' with the appropriate values for your Eclair node configuration.

Note that this code assumes you have an active Eclair node with the API enabled and a valid TLS certificate file (tls.cert).
