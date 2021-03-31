# Automatic duplicate proposal detection
## Members
Joel labad (badal@kth.se)

GitHub: [@LeeBadal](https://github.com/Pwoeakmd)

Paul Ginneh (johennin@kth.se)

GitHub [@johennin](https://github.com/Xdjgkhae)

## Proposal
We plan to create a github task that checks that no previous/similar proposals have been made previously.

To verify that the PR is a proposal we intend to test the folder structure or validate that a proposal label is assigned (if  https://github.com/KTH/devops-course/pull/949 is implemented)
We will then run a text comparator to previous PR(Title and description) proposals and notify the user/TA's by writing a comment if they are above a certain threshold of commonalities or if manual verification by a TA is required.

## Proposed tools
 * Github Actions
 * [NLTK](https://www.nltk.org/)
3
4
5

not 100%
