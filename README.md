
# Github Workflow for Building and Releasing a Minecraft Fabric Mod on Github

Example Workflow to build the jar of a Minecraft Fabric Mod and upload it to the release page of the Github repository.
Releases will be grouped together by major minecraft versions. Every new build release will either be attached to the corresponding major release version (that is used as a tag) or drafts a new release.

It's using the [realease-action@v1 from ncipollo](https://github.com/ncipollo/release-action).

Important changes I made that deviate from the Fabric-Example-Mod:
<ul>
  <li>Added tasks 'getMajorVersion' and 'getMinorVersion' to build.gradle (If you know a way of reading the versions directly from gradle.properties in a bash way, let me know)</li>
</ul>
