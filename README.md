# Getting Started with AI Observability

In this tutorial, you'll build a Retrieval-Augmented Generation (RAG) system using Cortex Search and Cortex LLMs. This will be the basis of our example. Then, you'll add OpenTelemetry tracing using TruLens to the app. Last, you'll create a test set and run LLM-as-judge evaluations in batch against your application.

Here is a summary of what you will be able to learn in each step by following this quickstart:

- **Setup Environment**: Create a snowflake objects required for the example.
- **Prepare data**: Load, parse and chunk data for RAG.
- **Search**: Create a Cortex Search service on top of the chunked data.
- **Create a RAG**: Create a RAG with Cortex Search and Complete, adding TruLens instrumentation.
- **Register the app**: Set application metadata for experiment tracking.
- **Create a run**: Configure your test set for evaluation.
- **Compute evaluation metrics**: Compute evaluation metrics in batch on the run.
- **Examine results**: Navigate AI Observability in Snowsight to view and compare traces and evaluation results.

## Related Resources

- [AI Observability Documentation](...)
- [Open Source TruLens Documentation](https://trulens.org/)
