# Getting Started with AI Observability

AI Observability in Snowflake Cortex enables you to easily evaluate and trace your gen AI applications. With AI Observability, you can measure the performance of your AI applications by running systematic evaluations, and iterate on your application configurations to optimize performance. In addition, you can log the application traces to debug your application. AI Observability improves trust and transparency of gen AI applications and agents, enabling thorough benchmarking and performance measurement prior to deploying your applications.

In this tutorial, you'll build a Retrieval-Augmented Generation (RAG) system using Cortex Search and Cortex LLMs. This will be the basis of our example. Then, you'll add OpenTelemetry tracing using TruLens to the app. Last, you'll create a test set and run LLM-as-judge evaluations in batch against your application.

Here is a summary of what you will be able to learn in each step by following this quickstart:

- **Setup Environment**: Create a snowflake objects required for the example.
- **Prepare data**: Load, parse and chunk data for RAG.
- **Create a RAG**: Create a RAG with Cortex Search and Complete, adding TruLens instrumentation.
- **Register the app**: Set application metadata for experiment tracking.
- **Create a run**: Configure your test set for evaluation.
- **Compute evaluation metrics**: Compute evaluation metrics in batch on the run.
- **Examine results**: Navigate AI Observability in Snowsight to view and compare traces and evaluation results.

## Related Resources

- [AI Observabilty Documentation](https://docs.snowflake.com/en/user-guide/snowflake-cortex/ai-observability)
- [Open Source TruLens Documentation](https://www.trulens.org/getting_started/)

