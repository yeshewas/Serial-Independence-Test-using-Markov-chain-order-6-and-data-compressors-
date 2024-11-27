the implementation include the following future:
  1.  Markov Order 5 Simulation:
        The simulate_markov_order5_with_prob function generates binary sequences based on a Markov process of order 5 with a conditional probability parameter pp.
        This effectively models dependency in the sequence.

    2. Entropy Calculation:
        The calculate_entropy function estimates the entropy of the sequence given the specified Markov order.
        It accounts for context-based symbol probabilities, which is essential for higher-order processes.

    3. Compression Testing:
        A variety of compressors (gzip, bzip2, zlib, brotli, zstd, lzfse, ppmd) are tested for their effectiveness in detecting serial dependencies.
        Each compressor's effectiveness is evaluated by comparing compressed sizes to entropy-based expectations.

    4. Null Hypothesis Testing:
        The test checks if the sequence is independent (null hypothesis) or shows dependencies.
        Rejection of the null hypothesis is based on whether the test statistic exceeds a threshold derived from the significance level αα.

    5. Results Presentation:
        Results are neatly organized into a pandas DataFrame and displayed for analysis.
