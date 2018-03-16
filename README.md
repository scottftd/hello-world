# hello-world
tutorial going through
<target name="all" description="Build, Gets and Deploys">
	<call target="mailBuild" />
	<call target="buildTFS" />
		 <call target="createbuildversion" />
		 <call target="getdeployfiles" />
		 <call target="mailDeploy" />
		 <call target="deployLM" />
		 <call target="mailCompile" />
		 <call target="compileSvc" />
		 <call target="compileApps" />
		 <call target="mailDone" />
	</target>
