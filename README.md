# TissueMicroscopyBench

**Benchmarking AI agents on tissue microscopy image analysis**

Tests whether AI agents can analyze real tissue microscopy images: locating cells and structures, quantifying staining and morphology, and reaching the conclusion a trained microscopist would. Each task pairs real image data with a specific analysis question, and the agent returns a structured answer that is graded deterministically. Scores show the share of attempts that reach the correct answer, counting refusals and errors as failures. A higher score means the model is more accurate at these tasks.

In this repo, there is 1 public example task that uses the same structure and content as benchmark questions.

## License

Apache 2.0 - see [LICENSE](LICENSE).
