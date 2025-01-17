## Ticket

## Short description of the PR

## Checklist

- In the worst case scenario, the severity of the production issue would be:

  - [ ] P1
  - [ ] P2
  - [ ] P3

- In the worst case scenario, the damages would include

  - Data

    - [ ] Corruption
    - [ ] Loss
    - [ ] Overflow
    - [ ] Leak
    - [ ] Other: _describe here_

  - Cyber security

    - [ ] Expose unwanted data to the consumer
      - [ ] Profiles (name, email, addresse, phone number)
      - [ ] Documents (passports / driver licenses)
      - [ ] Bank Info
    - [ ] Expose new ways of accessing the service (i.e. introducing an ftp endpoint)
    - [ ] Connection to a new external service

- Code

  - [ ] TeamCity build passes (restore, format &amp; compile)
  - [ ] I have reviewed my own PR
  - [ ] I have sorted all the TODOs
    - _List here the tickets to address the remaining TODOs_

- Database

  - [ ] The mongo queries generated:
    - [ ] Are indexed
    - [ ] Access read only collections

- Tests
  
  - [ ] I have tested it
  - Unit tests
    - [ ] Added for coverage
    - [ ] I'm fixing a bug, I added a unit test
    - [ ] Not necessary - Reason: _describe here_

- Cybersecurity

  - [ ] I did not introduce any `eval` or other custom code interpretation
  - I added some binary files
    - [ ] No
    - [ ] Added - Reason: _describe here_
  - [ ] I am not using the sysadmin token when not needed
  - [ ] I didn't hardcode any URLs / resource access path

- SonarQube:
  - Issues:
    - [ ] I have addressed the issues
    - [ ] I didn't address the issues: _describe here_
  - [ ] I have met the minimum coverage

## Related PRs
