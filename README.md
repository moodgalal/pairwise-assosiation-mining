# pairwise-assosiation-mining


Association rule mining
In this notebook, you'll implement the basic pairwise association rule mining algorithm.

To keep the implementation simple, you will apply your implementation to a simplified dataset, namely, letters ("items") in words ("receipts" or "baskets"). Having finished that code, you will then apply that code to some grocery store market basket data. If you write the code well, it will not be difficult to reuse building blocks from the letter case in the basket data case.

Problem definition
Let's say you have a fragment of text in some language. You wish to know whether there are association rules among the letters that appear in a word. In this problem:

Words are "receipts"
Letters within a word are "items"
You want to know whether there are association rules of the form, $a \implies b$, where $a$ and $b$ are letters. You will write code to do that by calculating for each rule its confidence, $\mathrm{conf}(a \implies b)$. "Confidence" will be another name for an estimate of the conditional probability of $b$ given $a$, or $\mathrm{Pr}[b \,|\, a]$.
