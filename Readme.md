## User Study: Identification of breaking changes in clients

Welcome to the user study on analyzing breaking update dependencies in a Java project using Maven!
In this study, we will explore how to identify compilation failures using the resources provided in this repository.

### Study Objective

- Identify compilation failures in a Java project using logs generated by Maven.
- Understand the bugs provided in a Java project through detailed explanations.

## Available Resources

In this repository, you will find the following resources:
1. Java project: [nem](./nem)
   - This folder contains the Java project that has compilation failures.
2. Maven Logs ([maven.log](./maven.log)):
   - The [`maven.log`](./maven.log) file contains Maven-generated logs during the build process of the original project. Participants are required to identify and count the number of breakages based on this file.
3. Explanations ([Explanation.md](./Explanation.md)):
   - The explanation file provides detailed explanations for each breaking update that was present in the project. Participants should use this explanation to identify each failure.

### Study Steps

1. Analyze the Maven logs provided in the [`maven.log`](./maven.log) file.
   - With the log file, identify the breakage in the Java project.
2. Refer to the [`Explanation.md`](./Explanation.md) file to understand the breaking changes in the project.
   - Use the explanations to identify the root cause of each breakage.
3. Answer the questions provided in the [KTH Form](https://www.kth.se/form/662828910e3340327ffb5a5f) in this link. https://www.kth.se/form/662828910e3340327ffb5a5f
   - The form contains two parts: 
     - Identification of breakage with log file.
     - Identification of breaking changes with explanations.
### Expected Output

- Number of compilation failures in the Java project.