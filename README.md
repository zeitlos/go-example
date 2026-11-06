# Go on Lucity

A standard-library HTTP service in one file. Lucity compiles it and runs the resulting binary,
with no runtime or package manager in the final image.

## Deploy it

1. Fork this repository.
2. In the [Lucity dashboard](https://lucity.cloud/app), click **New**, choose **GitHub Repository**, and pick your fork.
3. When the build finishes, open the service, go to **Settings**, and generate a platform domain.

The [Go guide](https://lucity.cloud/docs/guides/go) explains what the builder detects and what
is worth changing.

MIT licensed.
