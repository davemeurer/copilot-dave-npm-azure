# Black Duck CoPilot npm/Azure Pipelines Example
[![Build Status](https://blackducksoftware.visualstudio.com/copilot-dave-npm-azure/_apis/build/status/copilot-dave-npm-azure-CI)](https://blackducksoftware.visualstudio.com/copilot-dave-npm-azure/_build/latest?definitionId=10) [![Black Duck Security Risk](https://copilot.blackducksoftware.com/github/repos/davemeurer/copilot-dave-npm-azure/branches/master/badge-risk.svg)](https://copilot.blackducksoftware.com/github/repos/davemeurer/copilot-dave-npm-azure/branches/master)

Shows a working setup for using Black Duck CoPilot to analyze the risk of project dependencies



## Azure Pipelines Setup
The `azure-pipelines.yml` file has been modified to upload generated dependency data to CoPilot:

```yaml
- script: bash <(curl -s https://copilot-valid.blackducksoftware.com/ci/azure/scripts/upload)
```
