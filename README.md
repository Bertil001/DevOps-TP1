# DevOps-TP1
After opening 'DevOps TP01', you will have to set your environment variable 'PING_LISTEN_PORT' using 
'set PING_LISTEN_PORT={port}'
on Windows.

Then, at the project's root, you can open a terminal and run 
'npx ts-node index.ts'
 to launch the project or press button 'run' a the top right of the screen after open the file 'index.js'.  

In the terminal, you will see where your application is listening, it should match the 'PING_LISTEN_PORT' variable you just set.

Now, you can open a browser and search for 
http://localhost:{PING_LISTEN_PORT}/ping
, or open a terminal and write 
curl localhost:{PING_LISTEN_PORT}/ping -v
.

You will see the headers of your request on your browser's page or in your terminal.

If the route is wrong you will get a simple response with '404' status code. For any other error, you will receive a response with '500' status code.
