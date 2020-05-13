# CVE Details

This is a simple program to check multiple CVE's all at once and output it in a csv file.

**Below categories will be fetched:**

* CVSS Score
* Confidentiality Impact
* Integrity Impact
* Availability Impact
* Access Complexity
* Authentication
* Gained Access
* Vulnerability Type(s)
* CWE ID

# How to Use

1. You can download the files from <a href="https://mega.nz/file/rFNRAApB#09FrIKS8AsQJYj13gs5ontKLPyfNVlI9rOQ4swF1J_Q" target="_blank">cvedetails</a>.

    **Note:** GitHub doesn't allow uploading of file more than 25MB, so currently it has been uploaded to mega.co.nz.

2. Once Downloaded, you can save and then extract it.
3. Go into cvedetails Folder, you can see two files.
    * cvedetails.exe ( Which is the main executable ) 
    * cvedetails.csv ( A template in which you will enter list of CVE's )
4. Now all you have to do is enter the list of CVE's in cvedetails.csv and Save it.
    **Note:** Make sure, not to remove A1: CVE.
5. Once that's done, simply double click on cvedetails.exe it will pop-up a blank console window, wait for that to disappear, Now you can check cvedetails.csv file which will have all the required data.

# IMPORTANT THINGS TO NOTE

1. Do not delete A1 cell data which is **CVE** in cvedetails.csv file.
2. Both cvedetails.exe and cvedetails.csv has to be in same folder.
3. If the CVE is latest and there is not Entry for that on <a href="https://www.cvedetails.com/" target="_blank">CVE Details</a>, then the Entry will be blank for that CVE.
4. Incase <a href="https://www.cvedetails.com/" target="_blank">CVE Details</a> Website is down, then this will not work.

# Things to be added in future

1. Remove garbage/extra data.
2. Can execute from any place and take input from any file.
3. Links for Metasploit or any Exploit available.
4. Add more sources to fetch CVE details, other <a href="https://www.cvedetails.com/" target="_blank">CVE Details</a>.


# Credits

**<a href="https://www.cvedetails.com/" target="_blank">CVE Details</a>**

**Meet (Formatting the Output)**
