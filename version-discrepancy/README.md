# Version Discrepency Example

This example demos two federated apps that use two different versions of lodash.

- `app1` uses lodash@4.10.0.
- `app2` uses lodash@4.11.0 and `lodash.nth`--a feature not available in lodash@4.10.0.

# Running Demo
Run `yarn`
Run `yarn start`. 
This will build and serve both `app1` and `app2` on ports 3001 and 3002 respectively.

- [localhost:3001](http://localhost:3001/)
- [localhost:3002](http://localhost:3002/)
  <img src="https://ssl.google-analytics.com/collect?v=1&t=event&ec=email&ea=open&t=event&tid=UA-120967034-1&z=1589682154&cid=ae045149-9d17-0367-bbb0-11c41d92b411&dt=ModuleFederationExamples&dp=/email/VersionDiscrepency">
