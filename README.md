# vuln-list
Collect vulnerability information and save it in parsable format automatically

## Source

| Directory   | OS               |              Source             | URL                                                                                                                   |
|-------------|------------------|:-------------------------------:|-----------------------------------------------------------------------------------------------------------------------|
| alma/       | AlmaLinux        | AlmaLinux Errata                | https://errata.almalinux.org/8/errata.json                                                                                        |
| alpine/     | Alpine Linux     | Alpine secdb                    | https://secdb.alpinelinux.org/                                                                                        |
| amazon/1    | Amazon Linux     | Amazon Linux Security Center    | https://alas.aws.amazon.com/                                                                                          |
| amazon/2    | Amazon Linux 2   | Amazon Linux Security Center    | https://alas.aws.amazon.com/alas2.html                                                                                |
| arch-linux/ | Arch Linux       | Arch Linux Security Tracker     | https://security.archlinux.org/json                                                                                |
| debian/     | Debian GNU/Linux | Security Bug Tracker            | https://security-tracker.debian.org/tracker/                                                                          |
| nvd/        | -                | National Vulnerability Database | https://nvd.nist.gov/                                                                                                 |
| oval/debian | Debian GNU/Linux | OVAL                            | https://www.debian.org/security/oval/                                                                                 |
| oval/oracle | Oracle Linux     | OVAL                            | https://linux.oracle.com/security/oval/                                                                               |
| oval/redhat | RHEL/CentOS      | OVAL                            | https://www.redhat.com/security/data/oval/v2/                                                                         |
| redhat/     | RHEL/CentOS      | Security Data                   | https://www.redhat.com/security/data/metrics/                                                                         |
| rocky/      | Rocky Linux      | Rocky Linux UpdateInfo          | https://download.rockylinux.org/pub/rocky                                                                         |
| ubuntu/     | Ubuntu           | Ubuntu CVE Tracker              | https://people.canonical.com/~ubuntu-security/cve/                                                                    |
| cvrf/suse   | OpenSUSE/SLES    | SUSE Security CVRF              | http://ftp.suse.com/pub/projects/security/cvrf/                                                                       |
| photon/     | Photon           | Photon Security Advisory        | https://github.com/vmware/photon/wiki/Security-Advisories<br>https://packages.vmware.com/photon/photon_cve_metadata/  |
| ghsa/       | -                | GitHub Advisory Database        | https://github.com/advisories/                                                                                        |
| glad/       | -                | GitLab Advisory Database        | https://gitlab.com/gitlab-org/advisories-community/                                                                   |

## Update frequency
daily

## Update script
https://github.com/aquasecurity/vuln-list-update/

