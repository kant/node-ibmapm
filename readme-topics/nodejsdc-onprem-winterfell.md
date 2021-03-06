## Configuring on-premises Node.js applications monitoring using the Winterfell server

1. Install the Node.js data collector to your application by **either** of the following methods:

- Option 1:
    - a. In the `package.json` file of your Node.js application, add the following line to the dependencies section:
    <pre>"ibmapm":"^2.0.0"</pre>
    
    - b. Add the following line to the begining of the main file of your Node.js application:
    <pre>require('ibmapm');</pre>

- Option 2:
   - a. In the `package.json` file of your Node.js application, add the following line to the dependencies section:
    <pre>"appmetrics":"^4.0.0"</pre>
    
    - b. Add the following line to the begining of the main file of your Node.js application:
    <pre>require('appmetrics');</pre>
    
    **Tip:** If you start your application by running the node app.js command, `app.js` is the main file of your application.

2. Enable the Node.js data collector by specifying the server connection information with **either** of the following methods:

    Download the ICAM configure pack from ICAM extension, and extract the global.environment file.

- Option 1: Set the content of global.environment as environment variables to specify the Kubernetes ingress URL and your tenant ID, etc.

- Option 2: copy the gloal.environment to your root of application.

3. Run the following command to install all required dependencies:
    <pre>npm install</pre>

4. Restart the Node.js application.
