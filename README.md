# OIDC Backend

This project is an minimal OIDC server.  The when authentication requests are made this OIDC server contain custom interaction screens, which challenge the end user to prove  their identity.  Once the ID images and Selfie selfie scans have been captured by the camera, Incode evaluates the documents and then will issue an OIDC token containing identity verification results sending it to registered redirect URL.

For this project to work, there are a few things to know.

1) You can assign yourself a OIDC Client ID, Secret and Redirect   
2) The must assign yourself a OIDC Issue (Hostname)
 

The above environment variables are important as well as these which conntect the dirrect uses of technology together.


 3) API URL, API Client ID, Flow Id
 4) Redis Hostname and Port
 5) You also must assign a Hostname for the frontend interaction screens


## Prerequisites

This project has a minimum requirement of node v16.17.0 (Gallium).

## Useful Commands

To install required node packages run:

```

npm install

```

To run the project on localhost run:

```

npm run start

```




