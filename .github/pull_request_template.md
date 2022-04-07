## Links needed to approve a PR

### Artefact page

### Development Plan

### Task Tracker Tickets

### Unit Tests Data GitHub link (needed to merge in Develop)


## Link to approved PR in skyuk-dta-viewing-automated-tests


## Summary of the commit messages in this PR



- [ ] the PR is for develop AND Unit Tests have been passed

- [ ] the PR is for integration AND SIT have been passed

- [ ] the PR is for production AND UAT have been passed AND CR has been approved


## Confirm that all the following checks have been passed, if one or more checks were not applicable, explain why

- [ ] Check the count of stage table

- [ ] Check the count of archive table

- [ ] Archive table should not have header and footer

- [ ] Check the logic of monitoring timestamp if it is derived from source file name or header

- [ ] Required CC, FC or LF views should be created

- [ ] Check if all audit columns are populated correctly

- [ ] Check the schema of the archive table matches the stage table

- [ ] Check if the file is moved to processed folder

- [ ] Staging table should be truncated and loaded

- [ ] I have run the dos2unix command with all my files
