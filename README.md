# Learning Python and Investing Strategies

## Overview

My objective with this project is to learn Python, some visualization and test out some investment strategies. I will be breaking up the space into 3 areas:
1. Data gathering and processing
2. Evaluating investing strategies
3. Making recommendations

In each phase, we will produce data that can be consumed in future stages and also some visual interaction so I can play and learn more from the data.

[![](https://mermaid.ink/img/pako:eNpVUM1qwzAMfhXjw0igfYEcBm5TellHaXeLc9BsLTGLneCfQih99ynJRjOd7E_6fqQ7V71GXvDGw9Cyj510jEqILMsON_Qje2cn41LEkOf5X5Ntt69MLL-QPheuqM6-VxiCcU299KbSxqOKpnfs7fJEd6KqSojAzh4H8DAPvEjpDs4b1Vp0kaVJiZ0oXxfqleKeuNdIHGxGdrhBl5706-hii8H8I5REuKDqLcnqZfaIDleuRw96il2vE85b7sXaeIbKX4jE-IZb9BaMphPeJ1hy8rcoeUFPDf5bcukeNAcp9pRO8SL6hBueBoqCpQG6nuXFF3QBHz-8UXvt?type=png)](https://mermaid.live/edit#pako:eNpVUM1qwzAMfhXjw0igfYEcBm5TellHaXeLc9BsLTGLneCfQih99ynJRjOd7E_6fqQ7V71GXvDGw9Cyj510jEqILMsON_Qje2cn41LEkOf5X5Ntt69MLL-QPheuqM6-VxiCcU299KbSxqOKpnfs7fJEd6KqSojAzh4H8DAPvEjpDs4b1Vp0kaVJiZ0oXxfqleKeuNdIHGxGdrhBl5706-hii8H8I5REuKDqLcnqZfaIDleuRw96il2vE85b7sXaeIbKX4jE-IZb9BaMphPeJ1hy8rcoeUFPDf5bcukeNAcp9pRO8SL6hBueBoqCpQG6nuXFF3QBHz-8UXvt)

## The first stage is described by the following diagram

[![](https://mermaid.ink/img/pako:eNpVkU9PAjEQxb_KpBcggt45mLAseDIxoF62HMbtLDS0nU3_BFfCd7fLitEemk7y3m_mTc-iZkViLmDvsT3AayEd5FMsqpJPzjAq2OAJSowopWs8W2jZdHt295p3NzHMZo9QFNVYCnYEjTYELXlQ2GXXmD1wPOQ6OR0DcANRW5pIMbkRioGwrF48zVrPNYWg3T6b1_oTyHv2IRcLpWAbMTMsYUiewg2wHABlNf43QIhcHyc7-FGVg2pVbZKD55zc9FTMVAc1m2RdgDv4SN1DIGPAU_2bcTVY133Gt1ZhJMiRYNR32fZd-tvT6E-o9WB5qt51SGj0F133uBNTYclb1Cov_tyLpcgsS1LM81OhP0oh3SXrMEXedq4W8-gTTUW6di415u-yYt6gCXT5BpQVkYA?type=png)](https://mermaid.live/edit#pako:eNpVkU9PAjEQxb_KpBcggt45mLAseDIxoF62HMbtLDS0nU3_BFfCd7fLitEemk7y3m_mTc-iZkViLmDvsT3AayEd5FMsqpJPzjAq2OAJSowopWs8W2jZdHt295p3NzHMZo9QFNVYCnYEjTYELXlQ2GXXmD1wPOQ6OR0DcANRW5pIMbkRioGwrF48zVrPNYWg3T6b1_oTyHv2IRcLpWAbMTMsYUiewg2wHABlNf43QIhcHyc7-FGVg2pVbZKD55zc9FTMVAc1m2RdgDv4SN1DIGPAU_2bcTVY133Gt1ZhJMiRYNR32fZd-tvT6E-o9WB5qt51SGj0F133uBNTYclb1Cov_tyLpcgsS1LM81OhP0oh3SXrMEXedq4W8-gTTUW6di415u-yYt6gCXT5BpQVkYA)

## The second stage is described by the following diagram

[![](https://mermaid.ink/img/pako:eNpl0EtqwzAQBuCrDFq1EJO9F4VYdg8Qh26kLgZr4ojoYfQwpCF3r4oaQ6lWQnz_zGjubPKKWMvmgMsFTp10UA4_iGN2oN1KMWk3Q0wBE82a4udTQNO8Ae8E93bJiWCh0IzJT1eYUbu98XGzXbV8szzbbDDplf5jXnEvDkpBT0GvFVrCmAPFfQrk1Mb7ygfxUpoHgrFOepPSDSuaXMLewZFiNim-PlNDTb2LDx0zGv31J1i-cvbBopsIfruxHbNUnrQqy7r_VJEsXciSZG25KgxXyaR7FIc5-fHmJtamkGnH8qJK4V5j2bFl7RlNpMc3dh1-Ig?type=png)](https://mermaid.live/edit#pako:eNpl0EtqwzAQBuCrDFq1EJO9F4VYdg8Qh26kLgZr4ojoYfQwpCF3r4oaQ6lWQnz_zGjubPKKWMvmgMsFTp10UA4_iGN2oN1KMWk3Q0wBE82a4udTQNO8Ae8E93bJiWCh0IzJT1eYUbu98XGzXbV8szzbbDDplf5jXnEvDkpBT0GvFVrCmAPFfQrk1Mb7ygfxUpoHgrFOepPSDSuaXMLewZFiNim-PlNDTb2LDx0zGv31J1i-cvbBopsIfruxHbNUnrQqy7r_VJEsXciSZG25KgxXyaR7FIc5-fHmJtamkGnH8qJK4V5j2bFl7RlNpMc3dh1-Ig)

## The *third stage* is described by the following diagram:

[![](https://mermaid.ink/img/pako:eNpd0M9qwzAMBvBXET5t0LJ7DoOl7gs0vcU9qLGSmMZy8J-WUvruUwnpYD4J8_0-gR6qC5ZUpYaI8wjH2jDI0z9tQxlu5IYxJwgMKUfMNDhKcMZE9vUXKZfI6bQa2G6_QdetpitNYYYDdcETW8wucDKG37J5t624XvCu_WhyiCTdYv_w55rbLTnd7q84FSmBmWIfokfuCEL_D65ML2zfHpAvcC73r0TTBDeXR-gC986S-JPaKE_S5ayc5PGyRuWRPBlVyWgxXowy_JQclhyaO3eqyrHQRpVZNpJ2KJf0qupxSvT8BaXhdgU?type=png)](https://mermaid.live/edit#pako:eNpd0M9qwzAMBvBXET5t0LJ7DoOl7gs0vcU9qLGSmMZy8J-WUvruUwnpYD4J8_0-gR6qC5ZUpYaI8wjH2jDI0z9tQxlu5IYxJwgMKUfMNDhKcMZE9vUXKZfI6bQa2G6_QdetpitNYYYDdcETW8wucDKG37J5t624XvCu_WhyiCTdYv_w55rbLTnd7q84FSmBmWIfokfuCEL_D65ML2zfHpAvcC73r0TTBDeXR-gC986S-JPaKE_S5ayc5PGyRuWRPBlVyWgxXowy_JQclhyaO3eqyrHQRpVZNpJ2KJf0qupxSvT8BaXhdgU)
