---
title: "GAMER-2: a GPU-accelerated adaptive mesh refinement code -- accuracy, performance, and scalability"
date: 2017-12-01
publishDate: 2019-05-30T20:07:09.394810Z
authors: ["Hsi-Yu Schive", "John A ZuHone", "Nathan J Goldbaum", "Matthew J Turk", "Massimo Gaspari", "Chin-Yu Cheng"]
publication_types: ["2"]
abstract: "We present GAMER-2, a GPU-accelerated adaptive mesh refinement (AMR) code for astrophysics. It provides a rich set of features, including adaptive time-stepping, several hydrodynamic schemes, magnetohydrodynamics, self-gravity, particles, star formation, chemistry and radiative processes with GRACKLE, data analysis with yt, and memory pool for efficient object allocation. GAMER-2 is fully bitwise reproducible. For the performance optimization, it adopts hybrid OpenMP/MPI/GPU parallelization and utilizes overlapping CPU computation, GPU computation, and CPU-GPU communication. Load balancing is achieved using a Hilbert space-filling curve on a level-by-level basis without the need to duplicate the entire AMR hierarchy on each MPI process. To provide convincing demonstrations of the accuracy and performance of GAMER-2, we directly compare with Enzo on isolated disk galaxy simulations and with FLASH on galaxy cluster merger simulations. We show that the physical results obtained by different codes are in very good agreement, and GAMER-2 outperforms Enzo and FLASH by nearly one and two orders of magnitude, respectively, on the Blue Waters supercomputers using $1-256$ nodes. More importantly, GAMER-2 exhibits similar or even better parallel scalability compared to the other two codes. We also demonstrate good weak and strong scaling using up to 4096 GPUs and 65,536 CPU cores, and achieve a uniform resolution as high as $10,240^3$ cells. Furthermore, GAMER-2 can be adopted as an AMR+GPUs framework and has been extensively used for the wave dark matter ($ψ$DM) simulations. GAMER-2 is open source (available at https://github.com/gamer-project/gamer) and new contributions are welcome."
featured: false
publication: ""
tags: ["Authorship;DXL Member Papers"]
url_pdf: "http://arxiv.org/abs/1712.07070"
---
