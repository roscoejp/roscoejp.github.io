# roscoejp.github.io

## sample-terraform-registry
At attempt at creating a static TF registry using Github pages.

Thanks to https://github.com/caramelomartins/rekisteri for doing a lot of the heavy lifting and research.

You should be able to use the main.tf and `terraform init` to see this repo in action.

### Notes
- So far I've figured out how to render json using liquid, so now we can just use a (couple) big metadata files for each provider and selectively pull info from there as needed.
- Still need to figure out if liquid can be used to play around with routing or paths. Would be nice if I didn't have to create 100 pages for providers but just dump a file somewhere and abuse the Gitpages 404.
