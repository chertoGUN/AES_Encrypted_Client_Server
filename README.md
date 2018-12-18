C socket programming client/server model that implements pattern matching to check for strings in a file via AES encrypted communications. MISRA compliant.
HOW TO USE:
cd client_server  
cd client  
make  
cd ..  
cd server  
make  
./build/file  

OPEN A NEW TERMINAL  
cd client_server  
cd client  
USAGE FOR CLIENT  
./build/file <STRING_TO_SEARCH_HARDCODED_FILE_FOR_IN_client_server/src/server.c>  

TO IMPLEMENT FLAWFINDER AND SPLINT  
cd client_server  
cd client  
make security  
cd ..  
cd server  
make security  

HOW TO CLEAN BUILDS  
cd client_server  
cd client  
make clean  
cd ..  
cd server  
make clean  
