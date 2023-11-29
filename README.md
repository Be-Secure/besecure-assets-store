# BeS Assets Metadata Store
This repository maintains the metadata of all open source assets that are of interest to the BeSecure community. The assets are of interest to the community are Open Source Projects of Interests (POI), Vulnerabilities Of Interest (VOI), Machine Learning Models of Interest (MOI) and the publicly avaialble Training Datasets of Interest (DOI). These metadata is being used in [BeSLighthouse](https://github.com/Be-Secure/BeSLighthouse) to visualize the community tracked open source assets.

## Projects Of Interest (POI)
BeSecure community tracks the popular open source projects. The tracking involes forking the open source projects into BeSecure GitHub namespace and proactively assess each version source code for vulnerabilities. These are reported throught [BeSLighthouse](https://github.com/Be-Secure/BeSLighthouse). Various community projects in BeSecure provides tools to fasttrack remediation of known and unknown vulnerabilities of a particular version. The patched version source is distributed as a Trusted and Verified Open Source Software (TAVOSS). Each project version metadata is  available within the project-version directory. Once a new tracking request is received, add the project metadata entry into the project-metadata.json file and create a new file for the version summary within the project-version directory.

Schema to be added here

The community provided [BeSecure Contributor Toolkit](https://github.com/Be-Secure/besecure-developer-toolkit) can generate the metadata for the tracking of new project.

## Vulnerabilities Of Interest (VOI)
BeSecure community is interested in sharing the information about known vulnerabilities and the affected projects within its community members and other open source software security labs. Once a new vulnerability to be tracked is identified, add an entry into the vulnerabilities/vulnerability-metadata.json file

Schema to be added here

## Models Of Interest (MOI)
Pretrained machine learning models are available in various public platforms that can put to use for many useful usecases. These open source models may contain severe secutiry vulnerabilities. BeSecure community is offering a unique service in terms of identifying such models that are of interest to the community and proactively do a vulnerability assessment. Once a new ML model tracking request is received, add the model metadata entry into the models/model-metadata.json file.

Schema to be added here

## Datasets of Interest (DOI)
Publicly availbable training dataset that are of interest to the BeSecure community. Metadata schema is work in progress.
