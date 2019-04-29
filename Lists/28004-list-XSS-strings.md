XSS strings - used by 28004, Cross Site Scripting

| Cross-Site Scripting Search Strings                                                                 |
|-----------------------------------------------------------------------------------------------------|
| %0a%0a<script>alert(WILDCARD);</script>abc.jsp                                                      |
| %0d%0a%0d%0a<script>alert(WILDCARD)</script><!--                                                    |
| %22/%3E%3CSCRIPT%3Ealert%28%22WILDCARD%22%29%3C/SCRIPT%3E%3C%22&                                    |
| %3C/script%3E%3Cscript%3Ealert%28%27 AND %27%29%3C/script%3E                                        |
| %3C/script%3E%3Cscript%3Ealert%28/WILDCARD/%29%3C/script%3E%3Cscript%3E                             |
| %3Cscript%3Ealert%28%22WILDCARD%22%29;%3C/script%3E                                                 |
| %3Cscript%3Ealert%28%27WILDCARD%27%29%3C/script%3E                                                  |
| %3Cscript%3Ealert%28document.cookie%29%3C%2Fscript%3E                                               |
| %3Cscript%3Ealert%28document.domain%29%3B%3C%2Fscript%3E                                            |
| %3Cscript%3Ealert%28String.fromCharCode%2881,85,65,76,89,83,88,83,83,84,69,83,84%29%29%3C/script%3E |
| %3Cscript%3Ealert%28String.fromCharCode%28WILDCARD%29%29%3C/script%3E                               |
| %3Cscript%3Ealert%28WILDCARD%29%3C%2Fscript%3E                                                      |
| %3Cscript%3Ealert("WILDCARD")%3C/script%3E                                                          |
| %3Cscript%3Ealert(%22WILDCARD%22)%3C/script%3E                                                      |
| %3Cscript%3Ealert(%22WILDCARD%22);%3C/script                                                        |
| %3Cscript%3Ealert(%22WILDCARD%22);%3C/script%3E                                                     |
| %3Cscript%3Ealert(%22WILDCARDTest%22)%3C/script%3E                                                  |
| %3Cscript%3Ealert(%27WILDCARD%27)%3C/script%3E                                                      |
| %3Cscript%3Ealert(document.cookie)%3C/script%3E                                                     |
| %3Cscript%3Ealert(document.cookie);%3C/script%3E                                                    |
| %3Cscript%3Ealert('WILDCARD')%3C/script%3E                                                          |
| %3Cscript%3Ealert(WILDCARD);%3C/script%3E                                                           |
| %3CScRiPt%3Eprompt%28%27WILDCARD%27%29%3C/ScRiPt%3E                                                 |
| %3d"alert('WILDCARD');"%3d">                                                                        |
| %3E%3C/script%3E%3Cscript%3Ealert%28/WILDCARD/%29%3C/script%3E%3Cscript%3E%3C                       |
| %3E%3Cscript%3Ealert%28document.domain%29%3C%2Fscript%3E                                            |
| %3E%3Cscript%3Ealert%28document.domain%29%3C/script%3E                                              |
| %3E%3Cscript%3Ealert(document.cookie)%3C/script%3E                                                  |
| %db<script>alert(WILDCARD);</script>/                                                               |
| <%2Fscript><script>alert(WILDCARD))<%2Fscript>                                                      |
| </script>                                                                                           |
| </script><iframe+onload%3Dalert(%2FWILDCARD%2F)>                                                    |
| </script><script>alert(WILDCARD);</script>                                                          |
| </script><script>alert('WILDCARD');</script>                                                        |
| <\script>alert(document.domain)</script>                                                            |
| <script>*</script>                                                                                  |
| <script>alert("WILDCARD");</script>                                                                 |
| <script>alert("WILDCARD")</script                                                                   |
| <script>alert()</script>                                                                            |
| <script>alert(@)</script>                                                                           |
| <script>alert(document.cookie)</script>                                                             |
| <script>alert(document.domain);</script>                                                            |
| <script>alert(document.domain)</script>                                                             |
| <SCRIPT>alert(document.domain)</SCRIPT>                                                             |
| <script>alert(document.domain)</script>                                                             |
| <script>alert(document.domain)</script>                                                             |
| <script>alert(document.domain)</script>.asp                                                         |
| <script>alert(document.domain)</script>.bat                                                         |
| <script>alert(document.domain)</script>.cfm                                                         |
| <script>alert(document.domain)</script>.cgi                                                         |
| <script>alert(document.domain)</script>.exe                                                         |
| <script>alert(document.domain)</script>.html                                                        |
| <script>alert(document.domain)</script>.jsp                                                         |
| <script>alert(document.domain)</script>.php                                                         |
| <script>alert(document.domain)</script>.phtml                                                       |
| <script>alert(document.domain)</script>.pl                                                          |
| <script>alert(document.domain)</script>.shtml                                                       |
| <script>alert(document.domain)</script>.thtml                                                       |
| <script>alert(document.domain)</script><img%20src=                                                  |
| <script>alert(document.domain)</script><input+type="hidden                                          |
| <script>alert(WILDCARD);</script>                                                                   |
| <script>alert('WILDCARD');</script>                                                                 |
| <script>alert(WILDCARD)</script>                                                                    |
| <script>alert(WILDCARD)</script>                                                                    |
| <script>alert('WILDCARD')</script>                                                                  |
| <script>alert('WILDCARD')</script>&action=AttachFile                                                |
| <script>alert(WILDCARD)</script><!--                                                                |
| <script>alert(WILDCARD)</script></h1>                                                               |
| <script>alert(WILDCARD)</script><a%20href=                                                          |
| <script>alert*</script>                                                                             |
| <Script>javascript:alert(document.cookie)</Script>                                                  |
| ><script>alert("WILDCARD")%3B<%2Fscript>&volume="%2F><script>alert("WILDCARD")%3B<%2Fscript>#       |
| ><script>alert(/WILDCARD/);</script>                                                                |
| 3Cscript%3Ealert(document.cookie)%3C%2Fscript%3E&t_id=2                                             |
| cgi?file=%3Cscript%3Ealert(%22WILDCARD%22)%3C/script%3E%00                                          |
| E%3Cscript%3Ealert(WILDCARD)%3C/script%3E                                                           |
| onerror=alert%281%29%3E                                                                             |
| onerror=alert(1)%3E                                                                                 |
| onerror=alert(1)>                                                                                   |
| script>alert(document.domain)</script>                                                              |
| %3Cscript                                                                                           |
| %3C%2Fscript                                                                                        |
| script>                                                                                             |
| script%3E                                                                                           |
| SRC=javascript                                                                                      |
| IMG%20                                                                                              |
| %20ONLOAD=                                                                                          |
| INPUT%20                                                                                            |
| iframe%20                                                                                           |