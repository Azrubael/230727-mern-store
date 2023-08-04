An application with a microservice architecture: an ecommerce store of sorts.
The structure:
- frontend container (React 18.2);
- first backend container `notifications-api` (node.js 18.14, express 4.18, twilio 3.78);
- second backend container `products-api` (node.js 18.14, express 4.18, mongoose 6.4).

Before run you have to install Docker desctop and enable Kubernetes inside it options.

To start application on a localhost:
    $ ./k8s/apply-depl
    
To delete application infrastrucrure on a localhost
    $ ./k8s/delete-depl
    
    
>>> N.B.: The files listed below are left deliberately for convenience. They are not needed for the deployment to work.
- ./k8s/apply-pods
- ./k8s/delete-pods
- ./k8s/obsolete_store-pod.yaml
- ./k8s/tutor.yaml