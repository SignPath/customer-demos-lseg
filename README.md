# Demo walkthrough

From least to most secure

## Preparation

* Open Visual Studio Project in `VisualStudioSigning`
* Clean build-output folder

## Demo

### Visual Studio ClickOnce UI signing

Right-Click Project -> Publish then More Actions -> Edit -> Next..Next..Next - one can see the signing options
Publish

Signature visible on setup.exe and on VisualStudioSigning_1_0_0_0\VisualStudioSigning.dll.manifest -> Search for <Signature> block

## Jenkins Hash-Based

Run the pipeline, verification inline

## Jenkins File-Based

Run the pipeline, verification inline

SHOW SIGNPATH
