## Materials
* [Slides](https://yadi.sk/i/7TkZUDkt3GoPXE)
* The only relevant video-lecture we could find - [video](https://www.youtube.com/watch?v=2tKNpzUvDc4	)
* Will hopefully record our lecture in both russian and english soon!
* Self-critical sequence traning [original article](https://arxiv.org/abs/1612.00563)


## More materials
* An [awesome post](http://distill.pub/2016/augmented-rnns/) explaining attention and long-term memory models.
* [BLEU](http://www.aclweb.org/anthology/P02-1040.pdf) and [CIDEr](https://arxiv.org/pdf/1411.5726.pdf) articles.
* How _not_ to evaluate conversation models - [article](https://arxiv.org/abs/1603.08023)
* MSCOCO captioning [challenge](http://mscoco.org/dataset/#captions-challenge2015)
* Some articles on reinforcement learning for conversations: 
 * [task-oriented conversation system](https://arxiv.org/abs/1703.07055)
 * [generating dialogues](https://arxiv.org/abs/1606.01541)
* A large overview for machine translation (touching on RL, including RL failures) - [article](https://arxiv.org/abs/1609.08144)
* Overview of other non-games applications ("that review article") - https://arxiv.org/abs/1701.07274

## Homework

Homework assignment is described in the notebook.

Other frameworks: as usual, your task remains the same as in the main track:
- Implement or borrow seq2seq model for grapheme to phoneme task
  * Neat tenworflow [repo](https://github.com/cmusphinx/g2p-seq2seq)
  * __Important__ - this repo uses simplified phoneme dict - make sure you change preprocessing phase to meaningfully compare results.
- Implement self-critical sequence training ( = basic policy gradient with a special baseline, see notebook)
- Beat the benchmarks (notebook: last section)
  
Even if you decide to use custom frameworks, it is highly recommended that you reuse evaluation metrics (e.g. min Levenshtein) from the default assignment notebook