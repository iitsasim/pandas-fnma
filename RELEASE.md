Release Notes
=============

The list of changes to pandas between each release can be found
[here](https://pandas.pydata.org/pandas-docs/stable/whatsnew/index.html). For full
details, see the commit logs at https://github.com/pandas-dev/pandas.
#Issue CVE-2020-13091
**This project is to addres the cve #CVE-2020-13091 which is a seviory Critial with CVE Score 9.8**:
**Deatails:**
-----------
** DISPUTED ** pandas through 1.0.3 can unserialize and execute commands from an untrusted file that is passed to the read_pickle() function, if __reduce__ makes an os.system call. NOTE: third parties dispute this issue because the read_pickle() function is documented as unsafe and it is the user's responsibility to use the function in a secure manner.
For more details here https://nvd.nist.gov/vuln/detail/CVE-2020-13091
**Soltion**:
