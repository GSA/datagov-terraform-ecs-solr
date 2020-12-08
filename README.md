# datagov-terraform-ecs-solr

## Why this project

This repository supports an experiment in deploying Solr to AWS ECS using just `docker compose` (note: not the same as `docker-compose`). Here are the hypotheses to be tested:

1. [ ] We can deploy a production-ready Solr instance to AWS ECS [using just `docker compose`](https://aws.amazon.com/blogs/containers/deploy-applications-on-amazon-ecs-using-docker-compose/)
2. [ ] The compliance burden for getting an ATO with such a deployment is lower than getting an ATO with EKS in the mix
3. [ ] We can use Terraform to stand up and tear down duch deployments

- 

## Contributing

See [CONTRIBUTING](CONTRIBUTING.md) for additional information.

## Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
