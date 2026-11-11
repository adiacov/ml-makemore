# ml-makemore

My learning project: rebuilding **makemore** (a character-level language model that "makes more" of the things it's given, here names) step by step, following Andrej Karpathy's *Neural Networks: Zero to Hero* lectures. The goal is to understand each model, from bigrams up to a WaveNet-style network, by coding it myself in Jupyter notebooks.

## Lectures (in order)

1. [The spelled-out intro to language modeling: building makemore](https://www.youtube.com/watch?v=PaCmpygFfXo) (bigram model)
2. [Building makemore Part 2: MLP](https://www.youtube.com/watch?v=TCH_1BHY58I)
3. [Building makemore Part 3: Activations & Gradients, BatchNorm](https://www.youtube.com/watch?v=P6sfmUTpUmc)
4. [Building makemore Part 4: Becoming a Backprop Ninja](https://www.youtube.com/watch?v=q8SA3rM6ckI)
5. [Building makemore Part 5: Building a WaveNet](https://www.youtube.com/watch?v=t3YJ5hKiMQ0)

## Reference code

- makemore repo: https://github.com/karpathy/makemore
- Lecture notebooks: https://github.com/karpathy/nn-zero-to-hero/tree/master/lectures/makemore

## Setup

```bash
uv sync                  # creates .venv with torch (CPU), matplotlib, ipykernel
```

In VS Code, open a notebook in `notebooks/` and pick the `.venv` kernel.

## Layout

```
notebooks/   # my notebooks, one per lecture
data/        # names.txt dataset (from karpathy/makemore)
.dev/        # private scratch space for discussion and practice (git-ignored)
```
