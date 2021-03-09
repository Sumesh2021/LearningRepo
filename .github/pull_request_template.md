## Pull Request Guidelines

Filling out the template is required. Any pull request that does not include enough information to be reviewed may be closed at the maintainers' discretion

### Describe the Change

---
-Description of the changes


### Type of change

---

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to change)
- [ ] Docs change / refactoring / dependency upgrade

### Developer's Checklist

---

- [ ] I have linked this Pull Request with my Jira Card
- [ ] I have increased or maintained the existing code coverage
- [ ] Documentation has been added or updated (if needed)
- [ ] I have added unit tests to cover my changes
- [ ] I have added integration tests to cover my changes
- [ ] All new and existing tests passed
- [ ] Does this change impacts SLA or performance
- [ ] I have run the build locally and my branch build is green
- [ ] I have run the acceptance tests locally and tests are passing
- [ ] Is Logging & Monitoring added
- [ ] Is Production validation needed(If yes, then please mention validation steps in "Release Readiness" section)


### Test Result

---
Please add Test plan link below.

  - N/A


### Post-merge Checklist

- [ ] The [pipeline](https://spinnaker.expedia.biz/#/applications/lty-sterling-service-ec2/executions) is in a good state.
- [ ] Ensure the Integration [tests](https://ewe.builds.sb.karmalab.net/job/lty-sterling-service-ec2-joint.IntegrationTest) eventually pass.
- [ ] The AWS INT Acceptance [test](https://ewe.builds.sb.karmalab.net/job/lty-sterling-service-ec2-joint.AcceptanceTest/) is in a good state.
- [ ] The Sterling Perf [test](https://jenkins-eweperf.stress.expedia.com/job/Sterling-API-Perf-CapacityPlanning/) is in a good state. 



### Release Readiness

---
Please select an option

- [X] **Yes ready to be released without any dependencies or configurations**
      
- [ ] **No, this has additional dependencies/configuration work, as explained below** <br>

     ##### Feature Toggles/Configuration<br>
     - N/A
     
     ##### Dependent Services to be deployed first<br>
     - N/A
