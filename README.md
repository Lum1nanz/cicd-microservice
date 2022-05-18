# cicd-microservice
Microservice-Exercise for CI/CD@FHOOE

## Additional feature
Added a feature, to fetch the articles in a certain price-range specified via the `products/<lowerprice>/<higherprice>` GET-request.

## Changes made to the original code

The name of the `product` was changed to `Product` in the file `model.go` to allow the compiler the recognition of the struct in other files for simpler Unmarshalling.

Inside the `launch.json` file two configurations are stored for debugging and running the files. Those also include the environment-variables for postgres.