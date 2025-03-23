# Deploy Dynamic Apex

This repository contain GitHub Action designed to automate Salesforce deployment task. The action is packaged as a Docker container and provides a specialized function.

**cf-sf-deploy-dynamic-apex**

    Deploys Apex classes dynamically based on repository changes.

* **Inputs**:
    * **apex-directory**: Directory containing Apex classes.

Usage Example:

    - name: Deploy Apex Classes
      uses: ghcr.io/itfulcrum/cf-sf-deploy-dynamic-apex@latest
      with:
        apex-directory: "./src/classes"

## Installation & Usage

To use these GitHub Actions, ensure that your repository has:

* A .github/workflows/ directory for defining workflows.
* Necessary Salesforce authentication secrets configured in GitHub Actions.

## Contributing

Feel free to submit pull requests to improve existing actions or add new functionality.

## License

This project is licensed under the MIT License.