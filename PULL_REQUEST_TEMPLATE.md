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
  - [ ] The build passes
  - [ ] I have reviewed my own PR
  - [ ] I have sorted all the TODOs
    - Tickets to address the remaining TODOs
  - [ ] The size is reasonable
  - SonarQube:
    - [ ] I have addressed the issues
    - [ ] I have met the minimum coverage
  - Unit tests - new test(s) required for bugs
    - [ ] Added
    - [ ] Not necessary - Reason:
  - [ ] I have tested it
  - [ ] The mongo queries generated:
    - [ ] Are indexed
    - [ ] Access read only collections
  - [ ] I did not introduce any `eval` or other custom code interpretation
  - I added some binary files
    - [ ] No
    - [ ] Added - Reason:
  - [ ] I am not using the sysadmin token when not needed
  - [ ] No url hard coded

## Related PRs
