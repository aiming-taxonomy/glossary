# Contributing Guide

Thanks for choosing to help out and contribute to the aiming glossary

- Contributing to the Aiming Glossary is fairly easy. This document shows you how to get started

## Document type

The main document uses [Github flavoured markdown](https://guides.github.com/features/mastering-markdown/) so make sure it is styled correctly with appropriate headings and heiracy

## Submitting changes

- Fork the repo
  - <https://github.com/AnimaFPS/aiming-glossary/fork>
- Check out a new branch based and name it to what you intend to do:
  - Example:
    ```
    $ git checkout -b BRANCH_NAME
    ```
    If you get an error, you may need to fetch fooBar first by using
    ```
    $ git remote update && git fetch
    ```
  - Use one branch per fix / feature
- Commit your changes
  - Please provide a git message that explains what you've done
  - Commit to the forked repository
  - Example:
    ```
    $ git commit -am 'Add some fooBar'
    ```
- Push to the branch
  - Example:
    ```
    $ git push origin BRANCH_NAME
    ```
- Make a pull request
  - Make sure you send the PR to the <code>main</code> branch

If you follow these instructions, your PR will land pretty safely in the main repo!
