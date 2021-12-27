# Darts Tracker Backend Resources

Infrastructure resources for the Darts Tracker backend system.

#### Usage

To use this repo locally you need to have the [Serverless framework](https://serverless.com) installed.

``` bash
$ npm install serverless -g
```

Clone this repo.

``` bash
$ git clone https://github.com/adamldoyle/darts-tracker-resources
```

Go to one of the services in the `services/` dir.

And run this to deploy to your AWS account.

``` bash
$ serverless deploy
```

Once you deploy the resources in this repo, head over to [this accompanying repo](https://github.com/adamldoyle/darts-tracker-api) to deploy the API services.

#### Acknowledgements

Based on structure documented by [Serverless Stack](https://github.com/AnomalyInnovations/serverless-stack-demo-ext-api).

#### Maintainers

[Adam Doyle](mailto:adamldoyle@gmail.com)
