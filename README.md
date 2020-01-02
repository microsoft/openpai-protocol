OpenPAI Protocol
================

[OpenPAI](https://github.com/microsoft/pai) Protocol is a specification that includes:
- The resource requirement, including the docker image used by the job container, and the data used by the job, etc.
- Various requirement like the GPU/CPU usage, container role and job completion policy used by [Framework Controller](https://github.com/microsoft/frameworkcontroller).
- Scheduling requirement used by [Framework Controller](https://github.com/microsoft/frameworkcontroller) and [HiveD Scheduler](https://github.com/microsoft/hivedscheduler).
- Runtime environment variables, if needed.

OpenPAI protocol enables job sharing and portability: a job specified by the protocol can run in different OpenPAI deployment.
The protocol also allows users to make a template of a job, which further facilitates the sharing and collaboration in a team that has similar but slightly different configuration for a class of jobs.
With the protocol, OpenPAI introduces marketplace that hosts job or job templates that share with other people.


Contributing
------------

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
