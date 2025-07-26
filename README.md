# Deploy Express on Seenode in seconds

This is a repo for deploying a minimal but production-ready Node.js Express application for deployment on [Seenode](https://seenode.com).

This example demonstrates how to deploy a simple Express app.

### Deploy in minutes
View our [guide on deploying Express apps](https://seenode.com/docs/frameworks/javascript/express/) on [seenode](https://seenode.com) in seconds.


## How to Deploy on Seenode

1.  **Connect Your Repository**: Go to the [Seenode dashboard](https://cloud.seenode.com), select **New Web Service**, and choose this Git repository.
2.  **Confirm Settings**: Seenode will detect the Node.js environment and suggest the correct commands.
    *   **Build Command**: `npm install`
    *   **Start Command**: `node main.js`
3.  **Deploy**: Click **Create Web Service**.

That's it! Your Express app will be deployed and available at a public URL.

### Key Features on Seenode

*   **Production-Ready**: Your Express app runs in a managed Node.js environment. Seenode handles the infrastructure so you can focus on your code.
*   **Port Binding**: This example is configured to listen on port 80. Ensure your application code binds to this port, or whatever port you set when deploying your application.
*   **Seamless Scaling**: Scale your service horizontally or vertically with a few clicks from the Seenode dashboard as your traffic grows.
