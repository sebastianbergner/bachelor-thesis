# Bachelor Thesis

This repository contains the PDF of my Bachelor Thesis titled "Exploring Hypernetworks for Continual Learning from Demonstration".

## Abstract

Learning from demonstration (LfD) offers a natural and intuitive approach to teach robots a certain
skill, eliminating the need for explicit programming by a human instructor with expertise in robotics.
However, most works in the field of LfD only teach a single motion, which is impractical in real-world
situations. Recent work, such as those by Auddy et al. (2023a,b), address this limitation by proposing
methods using hypernetworks to enable learning of multiple real-world motions, but many aspects that
influence the performance of hypernetworks were not investigated thoroughly. The main objective of
this thesis is to do a deep dive into these aspects. Specifically focusing on optimizers, initializers, and
neural network architecture and investigating their effects on the continual learning process. We found
that Adam as optimizer and Kaiming as initializer in combination with a wider hypernetwork and
deeper targetnetwork were performing the best. These findings highlight the importance of a careful
selection of deep learning aspects in continual learning from demonstration.

## Acknowledgements

I would like to express my sincere gratitude to my supervisor, Sayantan Auddy, for their invaluable guidance, support, and encouragement throughout this research.

## Workshop Paper

We also published a workshop paper that got accepted, based on this thesis:

- **Title:** Effect of Optimizer, Initializer, and Architecture of Hypernetworks on Continual Learning from Demonstration
- **Conference:** Towards Efficient and Portable Robot Learning for Real-World Settings Workshop, European Robotics Forum 2024
- **Date:** 14.03.2024
- **Link:** [ArXiV Paper](https://arxiv.org/pdf/2401.00524.pdf)

## How to View

To view the full Bachelor Thesis, please download the [PDF file](./thesis.pdf).

## License

The code and materials are located in a separate [repository](https://github.com/sebastianbergner/ExploringCLFD) and are licensed under the MIT License.

This means you are free to use, modify, and distribute the code, provided you include the original copyright and license notice in any copy of the code or materials. 

The thesis document itself (thesis.pdf) remains under traditional copyright.

---

### Contact

For any questions or inquiries related to this thesis, feel free to contact:

Sebastian Bergner
sebastian.bergner@student.uibk.ac.at
[LinkedIn Profile](www.linkedin.com/in/sebastian-bergner-a96493186)
