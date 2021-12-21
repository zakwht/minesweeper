# Reinforcement Learning in Minesweeper

[![License](https://img.shields.io/github/license/zakwht/minesweeper)](/LICENSE.md)
[![Report](https://img.shields.io/badge/report-2021-orange.svg)](/report/report.pdf)

### Abstract
Minesweeper is a famous puzzle game involving a single player, requiring them to clear a board with hidden mines and numerical clues indicating the number of mines in the neighbourhood. We have implemented the Q learning and deep Q learning algorithms, ran several experiments on the reward structures, tuned hyperparameters, trained two final agents, and achieved different levels of success. Both the agents performed substantially better than a baseline random agent. Given the limitation of training time, the Q learning agent performed better in average reward and board completion rate, but the deep Q learning agent had a higher winning rate. The latter is likely to perform better if trained for longer, and is ultimately better suited for larger boards with continuous state spaces due to its ability to predict best actions for unseen states.

### Acknowledgments
* __Built in collaboration with__ J. Dudhat, N. Hird, S. Kosman, S. Theriault, and Y. Zhao
* __Designed under the instruction of__ [N. Mehta](http://web.uvic.ca/~nmehta/)

