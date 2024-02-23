{
    "policyversion": "2.1",
    "policyversiondate": "22.02.2024",
    "_liccluster": "deprecated in future releases",
    "liccluster": {
        "nocl" : ["mit", "bsd-3-clause", "apache-2.0","bsd-2-clause"],
        "lcl": ["lgpl-3.0", "lgpl-2.1" ,"mpl-1.1","mpl-2.0", "cddl-1.1", "cddl-1.0", "epl-2.0", "epl-1.0"],
        "hcl": ["#-gpl-2.0"],
        "ncl": ["agpl-3.0", "undefined","rejected", "gpl-2.0"],
        "rcl": ["?-apache-2.0","?-BSD-3.0"],
        "excl": ["!-gpl-2.0", "!-mit", "!-bsd-3-clause","!-agpl-3.0","!-agpl", "!-hpnd", "!-gpl-3.0"]
    },
    "licpolicy":
        {
                "nocl": {"border":"",
                        "reason":"ok",
                        "value": 0,
                        "lics": ["mit", "bsd-3-clause", "apache-2.0","bsd-2-clause"]},
                "excl": {"border":"", "reason":"freigegeben, wegen einer Ausnahme (Kundenauftrag), weil die SW veröffentlicht wird oder weil sie Teil eine Kaufproduktes ist",
                         "value": 1,
                         "lics": ["!-gpl-2.0", "!-mit", "!-bsd-3-clause","!-agpl-3.0","!-agpl", "!-hpnd", "!-gpl-3.0"]},
                "lcl":  {"border":"",
                        "reason":"Lizenz hat Bedingung",
                        "value": 3,
                        "lics": ["lgpl-3.0", "lgpl-2.1" ,"mpl-1.1","mpl-2.0", "cddl-1.1", "cddl-1.0", "epl-2.0", "epl-1.0"] },
                "hcl": {"border":"",
                        "reason":"ausschließlich BRZ interne Verwendung",
                        "value": 4,
                        "lics": ["#-gpl-2.0", "#-gpl-3.0"]},
                "ncl": {"border":"",
                        "reason":"Nicht erlaubte Lizenz",
                        "value": 10,
                        "lics": ["agpl-3.0", "undefined","rejected"]},
                "rcl": {"border":"",
                        "reason":"Lizenz nicht direkt abrufbar",
                        "value": 3,
                        "lics": ["?-apache-2.0","?-BSD-3.0"]},
                "undefined": {"border":"",
                              "reason":"undefinierte Lizenz",
                              "value": 6,
                              "lics": ["other", "undefined"]}              
            },
    "commitpolicy":
        {
            "fatal": {"reason":"Software veraltet (älter als vier Jahre)", "border":1460, "value": 10},
            "critical": {"reason":"Commit älter als ein Jahr", "border":365, "value": 3},
            "warning": {"reason":"Commit älter als 90 Tage", "border":90, "value": 2},
            "exception": {"reason":"Ausnahme", "border": "1970-01-01 00:00:00", "value": 2},
            "ok":{"reason":"ok", "border": 0, "value": 0},
            "not checked":{"reason":"not checked", "border": 0, "value": 0}
        },
    "archivedpolicy":
        {
            "fatal": {"reason":"archiviert", "border":1, "value": 10},
            "undefined": {"reason":"undefiniert", "border": 2, "value": 6},
            "exception": {"reason":"Ausnahme", "border": 3, "value": 1},
            "ok": {"reason":"ok", "border":0, "value": 0},
            "not checked":{"reason":"not checked", "border": 0, "value": 0}
        },
    "rejectedbyaadminpolicy":
        {
            "fatal": {"reason":"JA", "border":1, "value": 10},
            "ok": {"reason":"nein", "border":0, "value": 0}
        },
    "scorepolicy":
        {
            "fatal": {"reason":"Abgelehnt auf Grund von Score", "border":2, "value": 10},
            "critical": {"reason":"Risikoreich, benötigt Riskoabschätzung", "border":5, "value": 3},
            "warning": {"reason":"Unter Beobachtung", "border":7, "value": 2},
            "exception": {"reason":"Ausnahme oder manuelle Bewertung", "border":-1, "value": 1},
            "ok" : {"reason":"ok", "border":10, "value": 0}
        },
    "rejectpolicy":
        {
            "undefined": {"value": 6, "color": "grey"},
            "rejected": {"value": 10, "color": "violet"},
            "internal use only": {"value": 4, "color": "pink"},
            "critical": {"value": 3, "color": "red"},
            "warning": {"value": 2, "color": "yellow"},
            "exception": {"value": 1, "color": "blue"},
            "ok": {"value": 0, "color": "green"}
 
        }
}
