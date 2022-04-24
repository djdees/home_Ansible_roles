# pdf_server

## About
This role is to install an internal HTTP server to server pdfs for use at home.
It is not targeted for use on multiple servers, just to do the base set up of
one at home server.

## Steps:
1. Base install of Apache 2.x server from packaging system.
1. Deploy custom httpd.conf file.
1. Create content directory for pdfs.

## Notes:
- I generally run this from a VM on a Windows machine. I could add a task to
copy a host-guest shared file system's contents up to rapidly deploy PDFs.
- It would be easy to do it to a second server, if I felt the need to play with
availability.
- At some point, I will add OpenTelemetry so that I can work with metrics collection
on Apache HTTPd servers.
