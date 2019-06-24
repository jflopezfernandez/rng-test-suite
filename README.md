
# NIST SP 800-22 Test Suite

This is a fork of the original NIST SP 800-22 test suite developed by [Rukhin, et. al.](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-22r1a.pdf) at the [National Institute of Standards and Technology](https://www.nist.gov) (NIST). The original code may be found on the official [project page](https://csrc.nist.gov/projects/random-bit-generation/documentation-and-software) at the NIST Computer Security Resource Center site.

This repo is both a fork for easier access, as well as a host for a few fixes, such as refactoring the original makefile to allow for canonical usage, such as overriding the C compiler option via the `CC` variable.

 > <strong>Note: </strong> When using the samples from the data/ directory to derive the values from Appendix B the suite should be invoked with a stream length of 1,000,000 bits and there is one stream per file. For the tests that have parameters the default values should be used. Additionally, the results from the tables in Appendix B are not found in the `finalAnalysisReport.txt` file. They are in the results.txt files in the individual test directories (when running the sample data files these test directories are in the directory `experiments/AlgorithmTesting/`

#### External Links

 * [Download Official Documentation and Software](https://csrc.nist.gov/projects/random-bit-generation/documentation-and-software)
 * [Guide to the Statistical Tests](https://csrc.nist.gov/Projects/Random-Bit-Generation/Documentation-and-Software/Guide-to-the-Statistical-Tests)

#### Software Disclaimer

This software was developed at the National Institute of Standards and Technology by employees of the Federal Government in the course of their official duties. Pursuant to title 17 Section 105 of the United States Code this software is not subject to copyright protection and is in the public domain. The NIST Statistical Test Suite is an experimental system. NIST assumes no responsibility whatsoever for its use by other parties, and makes no guarantees, expressed or implied, about its quality, reliability, or any other characteristic. We would appreciate acknowledgment if the software is used.

#### Contact Information for the Original Authors

 * Ms. Elaine Barker 
 [elaine.barker@nist.gov](mailto:elaine.barker@nist.gov)
 * Lawrence Bassham
 [lawrence.bassham@nist.gov](mailto:lawrence.bassham@nist.gov)
