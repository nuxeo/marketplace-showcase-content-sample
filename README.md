# About feature

* What is it, what does it do / Abstract
* Project status: working/prototype
* Nuxeo Support

# Sub-modules organization

For complex projects, explains the organization of the project
Sample: https://github.com/nuxeo/nuxeo-template-rendering/blob/master/ReadMe.md

# Building

    mvn clean install

## Requirements

See [CORG/Compiling Nuxeo from sources](http://doc.nuxeo.com/x/xION)

Sample: https://github.com/nuxeo/nuxeo-distribution

## Limitations

Sample: https://github.com/nuxeo/nuxeo-elasticsearch/blob/master/README.md

## QA

[![Build Status](https://qa.nuxeo.org/jenkins/buildStatus/icon?job=addons_nuxeo-sample-project-master)](https://qa.nuxeo.org/jenkins/job/addons_nuxeo-sample-project-master/)

If QA resources are included, sample: https://github.com/nuxeo/nuxeo-sdk-ios/blob/master/README.md

## Deploying

Direct to MP package if any. Otherwise provide steps to deploy on Nuxeo Platform: copy JAR bundles into `$NUXEO_HOME/templates/custom/bundles/` and activate the `custom` template.
Sample: Install [the Sample Marketplace Package](https://connect.nuxeo.com/nuxeo/site/marketplace/package/nuxeo-sample).
Or manually copy the built artifacts into `$NUXEO_HOME/templates/custom/bundles/` and activate the "custom" template.

# Resources

## Documentation

## Reporting issues

Link to JIRA component (or project if there is no component for that project).
Sample: https://jira.nuxeo.com/browse/NXP/component/14503/
Sample: https://jira.nuxeo.com/secure/CreateIssue!default.jspa?project=NXP

# Licensing

[GNU Lesser General Public License (LGPL) v2.1](http://www.gnu.org/licenses/lgpl-2.1.html)

Sample: https://github.com/nuxeo/nuxeo-drive

# About Nuxeo

Nuxeo dramatically improves how content-based applications are built, managed and deployed, making customers more agile, innovative and successful. Nuxeo provides a next generation, enterprise ready platform for building traditional and cutting-edge content oriented applications. Combining a powerful application development environment with
SaaS-based tools and a modular architecture, the Nuxeo Platform and Products provide clear business value to some of the most recognizable brands including Verizon, Electronic Arts, Netflix, Sharp, FICO, the U.S. Navy, and Boeing. Nuxeo is headquartered in New York and Paris.
More information is available at [www.nuxeo.com](http://www.nuxeo.com).
