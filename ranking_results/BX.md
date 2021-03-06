## Experiments Results in BX

### Method List

[origin-ItemKNN](#origin-ItemKNN)　　　[5core-ItemKNN](#5core-ItemKNN)　　　[10core-ItemKNN](#10core-ItemKNN)  
[origin-PureSVD](#origin-PureSVD)　　　[5core-PureSVD](#5core-PureSVD)　　　[10core-PureSVD](#10core-PureSVD)  
[Origin-BPRMF](#origin-BPRMF)　　　[5core-BPRMF](#5core-BPRMF)　　　[10core-BPRMF](#10core-BPRMF)  
[Origin-BPRFM](#origin-BPRFM)　　　[5core-BPRFM](#5core-BPRFM)　　　[10core-BPRFM](#10core-BPRFM)  
[10core-SLIM](#10core-SLIM)  
[Origin-NeuMF](#origin-NeuMF)　　　[5core-NeuMF](#5core-NeuMF)　　　[10core-NeuMF](#10core-NeuMF)

---

<span id="origin-ItemKNN">origin-ItemKNN</span>

| metric@K | 1          | 5          | 10         | 20         | 30         | 50         |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| pre      | 0.05947461 | 0.03089164 | 0.02142179 | 0.01478315 | 0.01205327 | 0.00951546 |
| rec      | 0.01264055 | 0.02240922 | 0.02828692 | 0.03912287 | 0.05011961 | 0.06973284 |
| hr       | 0.05947461 | 0.08933067 | 0.10265546 | 0.12593226 | 0.14593131 | 0.18101278 |
| map      | 0.05947461 | 0.02538906 | 0.01587105 | 0.00953228 | 0.0070227  | 0.00477027 |
| mrr      | 0.05947461 | 0.09308465 | 0.10104907 | 0.10657174 | 0.10921163 | 0.11211135 |
| ndcg     | 0.05947461 | 0.07478626 | 0.07823961 | 0.08310166 | 0.08646921 | 0.09158947 |

<span id="5core-ItemKNN">5core-ItemKNN</span>

| metric@K | 1          | 5          | 10         | 20         | 30         | 50         |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| pre      | 0.11280923 | 0.06000238 | 0.04187678 | 0.02862155 | 0.02316246 | 0.0176118  |
| rec      | 0.02640871 | 0.05364587 | 0.06611443 | 0.08008965 | 0.09279935 | 0.11303398 |
| hr       | 0.11280923 | 0.1873216  | 0.21860133 | 0.25386537 | 0.281696   | 0.32136061 |
| map      | 0.11280923 | 0.046607   | 0.02834332 | 0.016671   | 0.0121753  | 0.00813312 |
| mrr      | 0.11280923 | 0.17808833 | 0.19374358 | 0.20426467 | 0.2091585  | 0.21387043 |
| ndcg     | 0.11280923 | 0.15018522 | 0.15802569 | 0.16455618 | 0.16888794 | 0.17423309 |

<span id="10core-ItemKNN">10core-ItemKNN</span>

| metric@K | 1          | 5          | 10         | 20         | 30         | 50         |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| pre      | 0.12924208 | 0.07317119 | 0.05164027 | 0.03646776 | 0.02960344 | 0.02270551 |
| rec      | 0.02634562 | 0.0614698  | 0.07855533 | 0.09957135 | 0.11451368 | 0.13606202 |
| hr       | 0.12924208 | 0.22926094 | 0.27799774 | 0.33078808 | 0.36415913 | 0.40808824 |
| map      | 0.12924208 | 0.05545532 | 0.0334547  | 0.01959314 | 0.01424467 | 0.00948878 |
| mrr      | 0.12924208 | 0.21167986 | 0.23143558 | 0.24597253 | 0.25230168 | 0.25859175 |
| ndcg     | 0.12924208 | 0.17907097 | 0.19207899 | 0.20167224 | 0.20652198 | 0.21209051 |

<span id="origin-PureSVD">origin-PureSVD</span>

| metric@K | 1          | 5          | 10         | 20         | 30         | 50         |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| pre      | 0.16248634 | 0.10295948 | 0.07757589 | 0.05558287 | 0.04479597 | 0.03379127 |
| rec      | 0.05512586 | 0.13423414 | 0.17609634 | 0.22081537 | 0.25052178 | 0.29509604 |
| hr       | 0.16248634 | 0.28105553 | 0.32471142 | 0.36632464 | 0.3942093  | 0.43475369 |
| map      | 0.16248634 | 0.08109045 | 0.05598261 | 0.03730756 | 0.02892684 | 0.0206906  |
| mrr      | 0.16248634 | 0.28334006 | 0.31777337 | 0.34079972 | 0.35011319 | 0.35897434 |
| ndcg     | 0.16248634 | 0.22302891 | 0.23437027 | 0.24112152 | 0.24455578 | 0.24882788 |

<span id="5core-PureSVD">5core-PureSVD</span>

| metric@K | 1          | 5          | 10         | 20         | 30         | 50         |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| pre      | 0.20611323 | 0.13377735 | 0.10295552 | 0.07545195 | 0.0617527  | 0.04679948 |
| rec      | 0.05044313 | 0.13204905 | 0.18333602 | 0.24158706 | 0.28082709 | 0.33424132 |
| hr       | 0.20611323 | 0.37505947 | 0.44796622 | 0.51135823 | 0.55019029 | 0.60079686 |
| map      | 0.20611323 | 0.10230455 | 0.06967823 | 0.04569943 | 0.03504672 | 0.02449732 |
| mrr      | 0.20611323 | 0.36404813 | 0.41148502 | 0.44442475 | 0.45816046 | 0.47063607 |
| ndcg     | 0.20611323 | 0.29161479 | 0.31049342 | 0.32023486 | 0.32441604 | 0.32886736 |

<span id="10core-PureSVD">10core-PureSVD</span>

| metric@K | 1          | 5          | 10         | 20         | 30         | 50         |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| pre      | 0.20880468 | 0.13831071 | 0.10792798 | 0.08014235 | 0.0659188  | 0.05034879 |
| rec      | 0.04065976 | 0.11191414 | 0.16215453 | 0.22154788 | 0.26094521 | 0.31934853 |
| hr       | 0.20880468 | 0.39159125 | 0.4739819  | 0.55260181 | 0.59276018 | 0.64809578 |
| map      | 0.20880468 | 0.10286482 | 0.06954565 | 0.04491957 | 0.03406623 | 0.0234681  |
| mrr      | 0.20880468 | 0.37134081 | 0.42226764 | 0.45797941 | 0.47301385 | 0.48680491 |
| ndcg     | 0.20880468 | 0.30043793 | 0.32158309 | 0.33460122 | 0.33868006 | 0.34317666 |

<span id="Origin-BPRMF">Origin-BPRMF</span>

| metric@K | 1          | 5          | 10         | 20         | 30         | 50         |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| pre      | 0.17859009 | 0.11684956 | 0.08996485 | 0.06587573 | 0.05329992 | 0.04005415 |
| rec      | 0.06811601 | 0.1755472  | 0.23765914 | 0.30770244 | 0.34818491 | 0.4022864  |
| hr       | 0.17859009 | 0.33630231 | 0.40083606 | 0.46211581 | 0.4947746  | 0.53645908 |
| map      | 0.17859009 | 0.08853578 | 0.06131849 | 0.04117636 | 0.03200582 | 0.02294873 |
| mrr      | 0.17859009 | 0.31671971 | 0.35822854 | 0.38689248 | 0.39816717 | 0.40852739 |
| ndcg     | 0.17859009 | 0.25926714 | 0.27677356 | 0.28791778 | 0.29219289 | 0.29653766 |

<span id="5core-BPRMF">5core-BPRMF</span>

| metric@K | 1          | 5          | 10         | 20         | 30         | 50         |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| pre      | 0.18173168 | 0.13057802 | 0.10634515 | 0.08272181 | 0.06996709 | 0.05506779 |
| rec      | 0.04705907 | 0.14463585 | 0.21874299 | 0.31049049 | 0.37781821 | 0.47070611 |
| hr       | 0.18173168 | 0.39640818 | 0.50172455 | 0.59996432 | 0.65895576 | 0.72882969 |
| map      | 0.18173168 | 0.09125416 | 0.0633934  | 0.0427982  | 0.03347344 | 0.02414851 |
| mrr      | 0.18173168 | 0.33923842 | 0.39307422 | 0.43333711 | 0.45112822 | 0.46789773 |
| ndcg     | 0.18173168 | 0.29040374 | 0.31991989 | 0.3386497  | 0.34720085 | 0.35530006 |

<span id="10core-BPRMF">10core-BPRMF</span>

| metric@K | 1          | 5          | 10         | 20         | 30         | 50         |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| pre      | 0.17458522 | 0.13148567 | 0.1087764  | 0.08621324 | 0.07307692 | 0.05812406 |
| rec      | 0.03603041 | 0.12216169 | 0.19049255 | 0.28413983 | 0.34562351 | 0.43750826 |
| hr       | 0.17458522 | 0.40516591 | 0.51923077 | 0.63207014 | 0.68797134 | 0.75669306 |
| map      | 0.17458522 | 0.08934672 | 0.06171426 | 0.04110051 | 0.03189759 | 0.02277883 |
| mrr      | 0.17458522 | 0.33612525 | 0.39283889 | 0.4361071  | 0.45484687 | 0.47308443 |
| ndcg     | 0.17458522 | 0.2914854  | 0.32413121 | 0.34693727 | 0.35501185 | 0.36294361 |

<span id="Origin-BPRFM">Origin-BPRFM</span>

| metric@K | 1          | 5          | 10         | 20         | 30         | 50         |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| pre      | 0.20424208 | 0.12925752 | 0.0983445  | 0.07109163 | 0.05726252 | 0.04246592 |
| rec      | 0.08922248 | 0.22672243 | 0.30691086 | 0.39364096 | 0.44216016 | 0.50407609 |
| hr       | 0.20424208 | 0.3890314  | 0.47040521 | 0.54933257 | 0.5903045  | 0.64080091 |
| map      | 0.20424208 | 0.09725737 | 0.0663311  | 0.04386746 | 0.03392933 | 0.02411069 |
| mrr      | 0.20424208 | 0.35544709 | 0.3999017  | 0.43000911 | 0.44187732 | 0.45229371 |
| ndcg     | 0.20424208 | 0.29902347 | 0.32165519 | 0.33700008 | 0.34300725 | 0.34919958 |

<span id="5core-BPRFM">5core-BPRFM</span>

| metric@K | 1          | 5          | 10         | 20         | 30         | 50         |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| pre      | 0.18131541 | 0.13137488 | 0.10844434 | 0.08408658 | 0.07084324 | 0.05539367 |
| rec      | 0.04580096 | 0.14266903 | 0.21911331 | 0.31519761 | 0.38214876 | 0.47099928 |
| hr       | 0.18131541 | 0.39955994 | 0.50166508 | 0.60567317 | 0.66490247 | 0.73061370 |
| map      | 0.18131541 | 0.09168134 | 0.06459097 | 0.04363535 | 0.03410374 | 0.02452018 |
| mrr      | 0.18131541 | 0.34067852 | 0.39683196 | 0.43770609 | 0.45546693 | 0.47197726 |
| ndcg     | 0.18131541 | 0.29179136 | 0.31998847 | 0.34050929 | 0.34930496 | 0.35660349 |

<span id="10core-BPRFM">10core-BPRFM</span>

| metric@K | 1          | 5          | 10         | 20         | 30         | 50         |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| pre      | 0.17062594 | 0.12763952 | 0.10665535 | 0.08450226 | 0.07222536 | 0.05754148 |
| rec      | 0.03386466 | 0.11590843 | 0.18127682 | 0.27199912 | 0.33478116 | 0.42641691 |
| hr       | 0.17062594 | 0.39790724 | 0.51046380 | 0.61972097 | 0.67826169 | 0.75084842 |
| map      | 0.17062594 | 0.08594080 | 0.05983547 | 0.04005209 | 0.03120502 | 0.02234348 |
| mrr      | 0.17062594 | 0.32620507 | 0.38252378 | 0.42508789 | 0.44415729 | 0.46230677 |
| ndcg     | 0.17062594 | 0.28540489 | 0.31759650 | 0.33934462 | 0.34802863 | 0.35647957 |

<span id="10core-SLIM">10core-SLIM</span>

| metric@K | 1          | 5          | 10         | 20         | 30         | 50         |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| pre      | 0.17637632 | 0.10324284 | 0.07525452 | 0.05303073 | 0.04291415 | 0.03221719 |
| rec      | 0.03478936 | 0.07795921 | 0.10135005 | 0.12552618 | 0.14359469 | 0.16907075 |
| hr       | 0.17637632 | 0.29835973 | 0.3474736  | 0.39206259 | 0.41892911 | 0.45446833 |
| map      | 0.17637632 | 0.08023473 | 0.05101032 | 0.03133856 | 0.02330235 | 0.01576797 |
| mrr      | 0.17637632 | 0.29514517 | 0.32635167 | 0.34736527 | 0.35644953 | 0.36467774 |
| ndcg     | 0.17637632 | 0.23861782 | 0.25036102 | 0.2571184  | 0.259869   | 0.26240472 |

<span id="Origin-NeuMF">Origin-NeuMF</span>

| metric@K | 1          | 5          | 10         | 20         | 30         | 50         |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| pre      | 0.18433804 | 0.11388533 | 0.08538787 | 0.06150658 | 0.04962551 | 0.03592038 |
| rec      | 0.08285618 | 0.20606551 | 0.27390643 | 0.34997359 | 0.39454559 | 0.42830297 |
| hr       | 0.18433804 | 0.35247732 | 0.42556173 | 0.50097383 | 0.54313334 | 0.57301316 |
| map      | 0.18433804 | 0.08559965 | 0.05748049 | 0.03761625 | 0.02897027 | 0.02044838 |
| mrr      | 0.18433804 | 0.31661798 | 0.35413926 | 0.37996101 | 0.39035028 | 0.39835576 |
| ndcg     | 0.18433804 | 0.2706136  | 0.29103615 | 0.30606662 | 0.31276658 | 0.31627819 |

<span id="5core-NeuMF">5core-NeuMF</span>

| metric@K | 1          | 5          | 10         | 20         | 30         | 50         |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| pre      | 0.13820171 | 0.10049952 | 0.08394386 | 0.06650809 | 0.05706074 | 0.04551142 |
| rec      | 0.03253906 | 0.10309809 | 0.16185529 | 0.23676601 | 0.29160058 | 0.36828171 |
| hr       | 0.13820171 | 0.31785205 | 0.41484301 | 0.50969315 | 0.56838725 | 0.6411156  |
| map      | 0.13820171 | 0.06864891 | 0.04800801 | 0.03265609 | 0.025778   | 0.01874915 |
| mrr      | 0.13820171 | 0.25999049 | 0.30409828 | 0.33752508 | 0.35282219 | 0.3672323  |
| ndcg     | 0.13820171 | 0.22918303 | 0.25709632 | 0.27650727 | 0.28611349 | 0.29616498 |

<span id="10core-NeuMF">10core-NeuMF</span>

| metric@K | 1          | 5          | 10         | 20         | 30         | 50         |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| pre      | 0.17279412 | 0.12669683 | 0.10570324 | 0.08316365 | 0.07117898 | 0.05634427 |
| rec      | 0.03439245 | 0.10731205 | 0.16837291 | 0.24548572 | 0.30271896 | 0.381575   |
| hr       | 0.17279412 | 0.38593514 | 0.49151584 | 0.58795249 | 0.64347662 | 0.70522247 |
| map      | 0.17279412 | 0.08721405 | 0.06101467 | 0.04094366 | 0.0319269  | 0.022796   |
| mrr      | 0.17279412 | 0.32764266 | 0.38311195 | 0.42456359 | 0.44344696 | 0.46087117 |
| ndcg     | 0.17279412 | 0.28161491 | 0.31093236 | 0.33009498 | 0.33772236 | 0.34419853 |
