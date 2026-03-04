Version 1.0 DRAFT
03/04/2026

****************************************************

                  OVAL Test Content

****************************************************

This content will be hosted on the new OVAL Community Github 
respository:  https://github.com/OVAL-Community/OVAL-Test-Content

This test content is derived from the original MITRE OVAL 
Test content released in 2013, and obtained from the archived 
OVAL Project github repository https://github.com/OVALProject/Test-Content

The MITRE Corporation developed the OVAL Test Content in 2013 to provide 
the OVAL Community with a simple way to test the capability of 
OVAL Definition Evaluators. After running the OVAL Test Content 
through an OVAL Definition Evaluator, the OVAL Results will show 
the user which tests are properly supported by that tool. This 
allows users to perform unit testing of tools against the OVAL
Language. Over time, the OVAL Test Content will cover the basic 
behavior of all tests and capabilities in the OVAL Language.

You may download the OVAL Test Content to any computer you wish, 
and to as many computers as you wish.  

BY USING THE OVAL TEST CONTENT, YOU SIGNIFY YOUR ACCEPTANCE OF THE 
TERMS AND CONDITIONS OF USE.  IF YOU DO NOT AGREE TO THESE TERMS, 
DO NOT USE THE OVAL TEST CONTENT.  SEE THE MITRE-TERMS.TXT FILE INCLUDED 
WITH THE OVAL TEST CONTENT.

PORTIONS OF THE OVAL TEST CONTENT HAVE BEEN DEVELOPED AND/OR UPDATED BY NIWC 
ATLANTIC, SEE NIWC-TermsOfUse.txt

-- CONTENTS --
	
  I     SUPPORTED PLATFORMS
         A. Linux 
         B. Sun Solaris
         C. Microsoft Windows
         D. MacOS
		 E. Cisco IOS and IOS XE
  II    USING THE OVAL TEST CONTENT
         A. Preparing the System
         B. Running the Content
         C. Expected Results
  III   REPORTING ISSUES
  IV    CONTRIBUTING

-- I -- SUPPORTED PLATFORMS --

  A. Linux

	  The OVAL Test Content is currently developed and tested on 
	  - ARM and x64 versions of Red Hat Enterprise Linux 7/8/9
	  - ARM and x64 versions of Oracle Linux 7/8/9
	  - ARM and x64 versions of Ubuntu 18/20/22/24
	  - ARM and x64 versions of SUSE Enterprise Linux 12/15
  
  B. Sun Solaris
  
	  The OVAL Test Content is currently developed and tested on 
	  - x86 and SPARC versions of Solaris 11
  
  C. Microsoft Windows
  
	  The OVAL Test Content is currently developed and tested on 
	  - 64 bit versions of Windows 10/11
	  - 64 bit versions of Windows 2016/2019/2022/2025

  D. Mac OS  

	  The OVAL Test Content is currently developed and tested on 
	  - macOS 13 or later.
	  
  E. Cisco IOS and IOS-XE
  
	  The OVAL test content is currently developed and tested 
	  against Cisco IOS 15 and Cisco IOS XE 17

-- II -- USING THE OVAL TEST CONTENT --

  A. Preparing the System
	  
	  First, extract the OVAL Test Content to a directory of your 
	  choice. Then unzip support.zip to the following location
	  depending on the platform of the system being tested.
	  
	  Windows: 
		unzip support.zip C: (will create a directory of 'support')
	
	  Linux, Mac OS, Solaris: 
		unzip support.zip to /opt (will create a subdirectory of 'support)
		untar unix_symlink_support.tarz to /opt
		
	  
	  For the Unix symlink_test, un-tar unix_symlink_support.tarz
	  into /opt/.

  B. Running the Content
  
	  Run each of the OVAL Definition documents in the platform 
	  directory of the system being tested against your OVAL 
	  Definition Evaluator.
	  
	  There are several directories of OVAL test content:
	  
	  - agnostic:	applicable to all platforms/OS
	  - aws:		applicable to all aws systems
	  - ios: 		applicable to Cisco IOS router/switch
	  - iosxe: 		applicable to Cisco IOS-XE router/switch
	  - junos: 		applicable to JunOS systems
	  - linux: 		applicable to linux systems
	  - macos: 		applicable to macOS systems
	  - panos:      applicable to all PanOS systems
	  - solaris:  	applicable to Sun Solaris systems
 	  - unix:    	applicable to all macOS, Linux and Solaris systems
	  - windows:    applicable to all Microsoft Windows systems

	  
  C. Expected Results

	 Each OVAL Definition document is written to evaluate to true unless
	 otherwise specified.
  
-- III -- REPORTING ISSUES --

	 Please report any issues to https://github.com/OVAL-Community/OVAL-Test-Content
	 
-- IV -- CONTRIBUTING --	 

	  Contributions to this test content are welcome and encouraged.  
	  
	  Many of the platforms have test content that is still needing to be developed.
	  Refer to each platform directory and look for a _TestContentNeeded.txt file.
	  
	  https://github.com/OVAL-Community/OVAL-Test-Content