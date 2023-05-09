# Evaluation

- **Status:** In Progress
- **Application Document:** https://github.com/w3f/Grants-Program/blob/master/applications/polkadot-contract-wizard.md
- **Milestone:** 1
- **Previously successfully merged evaluation:** All by keeganquigley

| Number | Deliverable | Accepted | Link | Notes |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| 0a    | License | <ul><li>[x] </li></ul> | <div><div>Frontend: https://github.com/protofire/polkadot-contract-wizard/blob/milestone-2/LICENSE</div><div>Backend: https://github.com/protofire/ink-compiler-be/blob/main/LICENSE</div></div> |  |
| 0b.    | Documentation | <ul><li>[x] </li></ul> | <div><div>Frontend: https://github.com/protofire/polkadot-contract-wizard/blob/milestone-2/README.md</div><div> Backend: https://github.com/protofire/ink-compiler-be/blob/main/README.md</div></div>  |  |
| 0c.    | Testing and Testing Guide | <ul><li>[x] </li></ul> | <div><div>Frontend: https://github.com/protofire/polkadot-contract-wizard/blob/milestone-2/tests/Readme.md</div><div> Backend: https://github.com/protofire/ink-compiler-be/blob/main/README.md#testing</div></div>  |  |
| 0d.    | Docker | <ul><li>[x] </li></ul> | https://github.com/protofire/polkadot-contract-wizard/blob/milestone-2/docker-compose.yml |  |
| 0e. | Article | <ul><li>[x] </li></ul> | https://medium.com/protofire-blog/introducing-the-polkadot-contract-wizard-a-game-changer-for-the-polkadot-and-kusama-ecosystem-fb9076880ca7 |  |
| 1. | Create a service that allows on demand contract compilation and deployment. | <ul><li>[x] </li></ul> | https://github.com/protofire/ink-compiler-be/tree/main |  |
| 2. | Develop Instance functionality. | <ul><li>[x] </li></ul> | https://github.com/protofire/polkadot-contract-wizard/tree/milestone-2 |  |

# General Notes

Docker fails when running `yarn build`:
```js
 => [3/4] RUN yarn install                                                                                          119.1s
 => ERROR [4/4] RUN yarn build                                                                                        0.8s
------
 > [4/4] RUN yarn build:
#0 0.423 yarn run v1.22.19
#0 0.444 $ next build
#0 0.752 `destination` does not start with `/`, `http://`, or `https://` for route {"source":"/api/:path*","destination":"undefined/:path*"}
#0 0.753
#0 0.753
#0 0.753 Error: Invalid rewrite found
#0 0.770 info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
#0 0.770 error Command failed with exit code 1.
------
failed to solve: process "/bin/sh -c yarn build" did not complete successfully: exit code: 1
```