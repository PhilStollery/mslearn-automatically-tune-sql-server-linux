---
page_type: sample
languages:
- sql
products:
- sql-server
description: "Scripts that illustrate how to monitor and automatically tune SQL Server on Linux for a learn module"
---

# Official Microsoft Sample

This repository contains sample scripts that show how administrators can use Azure Data Studio to monitor and tune the performance of SQL running on Linux. These scripts are used in the [Automatically tune SQL Server on Linux](https://docs.microsoft.com/learn/modules/automatically-tune-sql-server-linux/) learn module.

## Contents

Outline the file contents of the repository. It helps users navigate the codebase, build configuration and any related assets.

| File/folder        | Description                                |
|--------------------|--------------------------------------------|
| `.gitignore`       | Define what to ignore at commit time.      |
| `CODE_OF_CONDUCT.md` | Conventions for the Microsoft Open Source Code of Conduct |
| `LICENSE`          | The license for the sample.                |
| `README.md`        | This README file.                          |
| `SECURITY.md`      | How to report security vulnerabilities     |
| `auto_tune.sql`    | Enables autotune for a database            |
| `batchrequests.sql` | Queries performance data                  |
| `batchrequests_perf_collector.sql` | Creates a table to store performance data |
| `cpwwi.sh`         | Copies the Wide World Importers database   |
| `initialize.sql`   | Executes the initialize stored procedure   |
| `recommendations.sql` | Retrieves automatic tuning recommendations |
| `regression.sql`   | Executes the regression stored procedure   |
| `report.sql`       | Obtains a report for a package type ID     |
| `restorewwi.sh`    | Restores the Wide World Importers database |
| `restorewwi_linux.sql` | Restores the Wide World Importers database on Linux servers |
| `setup.sql`  | Sets up resources for the exercise. |

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
