# x0.monster-Filehost
x0.monster - Filehost.

Hi,
next little project we want to show-off is [https://x0.monster/](https://x0.monster/ "https://x0.monster/")

![](https://x0.monster/nUtpUc_Erm2b.png "")
<pre>
 === How To Upload ===
You can upload files to this site via a simple HTTPS POST, e.g. using curl:
curl -F "file=@/path/to/your/file.jpg" https://x0.monster/

Or if you want to pipe to curl *and* have a file extension, add a "filename":
echo "hello" | curl -F "file=@-;filename=.txt" https://x0.monster/

On Windows, you can use ShareX and import this custom uploader - https://x0.monster/?sharex

Or simply choose a file and click "Upload" on the site.

 === File Sizes & Retention ===
The maximum allowed file size is 10 MiB.

Files are kept for a minimum of 31, and a maximum of 365 Days.

How long a file is kept depends on its size. Larger files are deleted earlier
than small ones. This relation is non-linear and skewed in favour of small
files.

 === Terms Of Service ===
x0 is NOT a platform for:
    * piracy
    * extremist material of any kind
    * malware / botnet C&C
    * doxxing, database dumps containing personal information
    * anything illegal

Uploads found to be in violation of these rules will be removed,
and the originating IP address blocked from further uploads.

Note that Tor exit nodes are blocked by the firewall due to frequent rule violations.

 === Contact ===
If you want to report abuse of this service, or have any other inquiries,
please write an email to x0.monster@proton.me
</pre>
