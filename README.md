#Scribbles
==========

**On 28 April, 2017 [Wikileaks](https://wikileaks.org/vault7/#Scribbles) published**

Today, April 28th 2017, WikiLeaks publishes the documentation and source code for CIA's "Scribbles" project, a document-watermarking preprocessing system to embed "Web beacon"-style tags into documents that are likely to be copied by Insiders, Whistleblowers, Journalists or others. The released version (v1.0 RC1) is dated March, 1st 2016 and classified SECRET//ORCON/NOFORN until 2066.

Scribbles is intended for off-line preprocessing of Microsoft Office documents. For reasons of operational security the user guide demands that "[t]he Scribbles executable, parameter files, receipts and log files should not be installed on a target machine, nor left in a location where it might be collected by an adversary."

According to the documentation, "the Scribbles document watermarking tool has been successfully tested on [...] Microsoft Office 2013 (on Windows 8.1 x64), documents from Office versions 97-2016 (Office 95 documents will not work!) [and d]ocuments that are not be locked forms, encrypted, or password-protected". But this limitation to Microsoft Office documents seems to create problems: "If the targeted end-user opens them up in a different application, such as OpenOffice or LibreOffice, the watermark images and URLs may be visible to the end-user. For this reason, always make sure that the host names and URL components are logically consistent with the original content. If you are concerned that the targeted end-user may open these documents in a non-Microsoft Office application, please take some test documents and evaluate them in the likely application before deploying them."

Security researches and forensic experts will find more detailed information on how watermarks are applied to documents in the source code, which is included in this publication as a zipped archive.
