# HyperV-Report

.EXAMPLE
		Creates a Hyper-V Cluster report in the working directory.
		.\Get-HyperVReport.ps1 -Cluster Hvcluster1
	.EXAMPLE
		Creates a Hyper-V Cluster report that shown only highlighted events and alerts in the working directory.
		.\Get-HyperVReport.ps1 -Cluster Hvcluster1 -HighlightsOnly $true
	.EXAMPLE
		Creates one or more standalone Hyper-V Host(s) report in the working directory.
		.\Get-HyperVReport.ps1 -VMHost Host1,Host2,Host3
	.EXAMPLE
		Creates a Hyper-V Cluster report with custom file name prefix and saves is to the specified folder.
		.\Get-HyperVReport.ps1 -Cluster Hvcluster1 -ReportFileNamePrefix HvReport -ReportFilePath c:\tools
