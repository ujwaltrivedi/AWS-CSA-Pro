# AWS CSA Pro


## AWS ECS

### AWS EC2 Launch Type
* bridge is software defined networking type (slow)
* host networking maps container port to host port 1:1 (only 1 instance of container of same type can run on a given host)
* `awsvpc` networking mode (very high performance)
* networking mode `awsvpc` is an elastic network interface (some instances have limits on how many ENIs can be attached)

### AWS Fargate  Launch Type

#### Linux
* only supports networking mode `awsvpc`

#### Windows
* only supports NAT networking type
