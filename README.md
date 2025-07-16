

## INSTRUCTIONS

### Create backend image

Navigate to backend folder and type:

``` docker build -t backend . ```

### Create frontend image

Navigate to frontend folder and type:

``` docker build -t frontend . ```

### Deploy kubernetes

Navigate to kubernetes folder. 

Apply the kubernetes files in following order:

``` kubectl apply -f database.yaml ```

``` kubectl apply -f backend.yaml ```

``` kubectl apply -f frontend.yaml ```

Enjoy!
