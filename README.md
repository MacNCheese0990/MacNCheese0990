<svg xmlns="http://www.w3.org/2000/svg"
     viewBox="0 0 1441 302"
     width="1441"
     height="302"
     style="background:#000000">

    <metadata><![CDATA[{"width":1441,"height":302,"backgroundColor":"#000000","avatarUrl":"https://avatars.githubusercontent.com/u/69421356?v=4","avatarSize":95,"particleCount":2,"particleColor":"#f59e0b","waveColorStart":"#ff0000","waveColorMid":"#ff0000","waveColorEnd":"#f59e0b","glowColorStart":"#f59e0b","glowColorMid":"#f59e0b","glowColorEnd":"#f59e0b","borderEnabled":true,"borderColor":"#f59e0b","borderRadius":2,"borderSize":2,"meteors":[{"id":"1784477130648","iconSlug":"mdi:github","iconColor":"","trailColor":"#888888","startX":706.7985296445254,"angle":75,"duration":10,"delay":0.1,"iconUrl":"https://api.iconify.design/mdi/github.svg"},{"id":"1784477207461","iconSlug":"arcticons:ibispaint-x","iconColor":"","trailColor":"#888888","startX":1103.3742641122,"angle":75,"duration":10,"delay":5.1,"iconUrl":"https://api.iconify.design/arcticons/ibispaint-x.svg"},{"id":"1784477258927","iconSlug":"simple-icons:carrd","iconColor":"","trailColor":"#888888","startX":183.37480746996573,"angle":75,"duration":10,"delay":9.1,"iconUrl":"https://api.iconify.design/simple-icons/carrd.svg"}]}]]></metadata>

    <defs>
        <!-- Glow -->
        <filter id="glow">
            <feGaussianBlur stdDeviation="4" result="blur"/>
            <feMerge>
                <feMergeNode in="blur"/>
                <feMergeNode in="SourceGraphic"/>
            </feMerge>
        </filter>

        <!-- Stronger glow for meteors -->
        <filter id="meteorGlow">
            <feGaussianBlur stdDeviation="3" result="blur"/>
            <feMerge>
                <feMergeNode in="blur"/>
                <feMergeNode in="blur"/>
                <feMergeNode in="SourceGraphic"/>
            </feMerge>
        </filter>

        <!-- Gradient for waves -->
        <linearGradient id="waveGrad" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#ff0000"/>
            <stop offset="50%" stop-color="#ff0000"/>
            <stop offset="100%" stop-color="#f59e0b"/>
        </linearGradient>

        <!-- Gradient for glowing circle -->
        <linearGradient id="glowGrad" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#f59e0b"/>
            <stop offset="50%" stop-color="#f59e0b"/>
            <stop offset="100%" stop-color="#f59e0b"/>
        </linearGradient>

        <!-- Meteor trail gradients -->
        
        <linearGradient id="trail-1784477130648" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#888888" stop-opacity="0"/>
            <stop offset="100%" stop-color="#888888" stop-opacity="1"/>
        </linearGradient>

        <linearGradient id="trail-1784477207461" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#888888" stop-opacity="0"/>
            <stop offset="100%" stop-color="#888888" stop-opacity="1"/>
        </linearGradient>

        <linearGradient id="trail-1784477258927" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#888888" stop-opacity="0"/>
            <stop offset="100%" stop-color="#888888" stop-opacity="1"/>
        </linearGradient>

        <!-- Circle clip for avatar -->
        <clipPath id="avatarClip">
            <circle cx="720.5" cy="151" r="47.5"/>
        </clipPath>
    </defs>

    <!-- Background waves -->
    <path d="M0 151 Q180 121 360 151 T721 151 T1081 151 T1441 151"
          fill="none"
          stroke="url(#waveGrad)"
          stroke-width="2"
          opacity="0.5">
        <animate attributeName="d"
                 dur="6s"
                 repeatCount="indefinite"
                 values="
             M0 151 Q180 121 360 151 T721 151 T1081 151 T1441 151;
             M0 151 Q180 181 360 151 T721 151 T1081 151 T1441 151;
             M0 151 Q180 121 360 151 T721 151 T1081 151 T1441 151"/>
    </path>

    <!-- ========== METEOR LOGOS ========== -->
    
            <!-- mdi:github Meteor -->
            <g filter="url(#meteorGlow)" visibility="hidden">
                <line x1="706.7985296445254" y1="-50" x2="719.7394818996514" y2="-1.7037086855465873" stroke="url(#trail-1784477130648)" stroke-width="2" stroke-linecap="round">
                    <animate attributeName="x1" values="706.7985296445254;823.7847380308648" dur="10s" repeatCount="indefinite" begin="0.1s"/>
                    <animate attributeName="y1" values="-50;386.5984734826589" dur="10s" repeatCount="indefinite" begin="0.1s"/>
                    <animate attributeName="x2" values="719.7394818996514;836.7256902859908" dur="10s" repeatCount="indefinite" begin="0.1s"/>
                    <animate attributeName="y2" values="-1.7037086855465873;434.8947647971123" dur="10s" repeatCount="indefinite" begin="0.1s"/>
                </line>
                <image href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9ImN1cnJlbnRDb2xvciIgZD0iTTEyIDJBMTAgMTAgMCAwIDAgMiAxMmMwIDQuNDIgMi44NyA4LjE3IDYuODQgOS41Yy41LjA4LjY2LS4yMy42Ni0uNXYtMS42OWMtMi43Ny42LTMuMzYtMS4zNC0zLjM2LTEuMzRjLS40Ni0xLjE2LTEuMTEtMS40Ny0xLjExLTEuNDdjLS45MS0uNjIuMDctLjYuMDctLjZjMSAuMDcgMS41MyAxLjAzIDEuNTMgMS4wM2MuODcgMS41MiAyLjM0IDEuMDcgMi45MS44M2MuMDktLjY1LjM1LTEuMDkuNjMtMS4zNGMtMi4yMi0uMjUtNC41NS0xLjExLTQuNTUtNC45MmMwLTEuMTEuMzgtMiAxLjAzLTIuNzFjLS4xLS4yNS0uNDUtMS4yOS4xLTIuNjRjMCAwIC44NC0uMjcgMi43NSAxLjAyYy43OS0uMjIgMS42NS0uMzMgMi41LS4zM3MxLjcxLjExIDIuNS4zM2MxLjkxLTEuMjkgMi43NS0xLjAyIDIuNzUtMS4wMmMuNTUgMS4zNS4yIDIuMzkuMSAyLjY0Yy42NS43MSAxLjAzIDEuNiAxLjAzIDIuNzFjMCAzLjgyLTIuMzQgNC42Ni00LjU3IDQuOTFjLjM2LjMxLjY5LjkyLjY5IDEuODVWMjFjMCAuMjcuMTYuNTkuNjcuNUMxOS4xNCAyMC4xNiAyMiAxNi40MiAyMiAxMkExMCAxMCAwIDAgMCAxMiAyIi8+PC9zdmc+" width="32" height="32" x="703.7394818996514" y="-17.703708685546587" >
                    <animate attributeName="x" values="703.7394818996514;820.7256902859908" dur="10s" repeatCount="indefinite" begin="0.1s"/>
                    <animate attributeName="y" values="-17.703708685546587;418.8947647971123" dur="10s" repeatCount="indefinite" begin="0.1s"/>
                </image>
                <set attributeName="visibility" to="visible" begin="0.1s"/>
            </g>

            <!-- arcticons:ibispaint-x Meteor -->
            <g filter="url(#meteorGlow)" visibility="hidden">
                <line x1="1103.3742641122" y1="-50" x2="1116.3152163673262" y2="-1.7037086855465873" stroke="url(#trail-1784477207461)" stroke-width="2" stroke-linecap="round">
                    <animate attributeName="x1" values="1103.3742641122;1220.3604724985394" dur="10s" repeatCount="indefinite" begin="5.1s"/>
                    <animate attributeName="y1" values="-50;386.5984734826589" dur="10s" repeatCount="indefinite" begin="5.1s"/>
                    <animate attributeName="x2" values="1116.3152163673262;1233.3014247536655" dur="10s" repeatCount="indefinite" begin="5.1s"/>
                    <animate attributeName="y2" values="-1.7037086855465873;434.8947647971123" dur="10s" repeatCount="indefinite" begin="5.1s"/>
                </line>
                <image href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgNDggNDgiPjxwYXRoIGZpbGw9Im5vbmUiIHN0cm9rZT0iY3VycmVudENvbG9yIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiIGQ9Ik0yNy44NzUgMzMuNWExNC41IDE0LjUgMCAxIDEgMTQuNS0xNC41YTE0LjUxNyAxNC41MTcgMCAwIDEtMTQuNSAxNC41bTAtMjFhNi41IDYuNSAwIDEgMCA2LjUgNi41YTYuNTEgNi41MSAwIDAgMC02LjUtNi41Ii8+PHBhdGggZmlsbD0ibm9uZSIgc3Ryb2tlPSJjdXJyZW50Q29sb3IiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgZD0iTTIxLjM3NSAzMS45NTdWMzkuNWE0IDQgMCAwIDEtOCAwVjE5bS03IDIzLjVWMjIiLz48Y2lyY2xlIGN4PSI2LjM3NSIgY3k9IjE5IiByPSIuNzUiIGZpbGw9ImN1cnJlbnRDb2xvciIvPjxwYXRoIGZpbGw9Im5vbmUiIHN0cm9rZT0iY3VycmVudENvbG9yIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiIGQ9Ik0yNy44NzUgMjUuNXY4bS00LjU5Ni05LjkwNGwtNS42NTcgNS42NTdNMjEuMzc1IDE5aC04bTkuOTA0LTQuNTk2bC01LjY1Ny01LjY1N00yNy44NzUgMTIuNXYtOG00LjU5NiA5LjkwNGw1LjY1Ny01LjY1N00zNC4zNzUgMTloOG0tOS45MDQgNC41OTZsNS42NTcgNS42NTciLz48L3N2Zz4=" width="32" height="32" x="1100.3152163673262" y="-17.703708685546587" >
                    <animate attributeName="x" values="1100.3152163673262;1217.3014247536655" dur="10s" repeatCount="indefinite" begin="5.1s"/>
                    <animate attributeName="y" values="-17.703708685546587;418.8947647971123" dur="10s" repeatCount="indefinite" begin="5.1s"/>
                </image>
                <set attributeName="visibility" to="visible" begin="5.1s"/>
            </g>

            <!-- simple-icons:carrd Meteor -->
            <g filter="url(#meteorGlow)" visibility="hidden">
                <line x1="183.37480746996573" y1="-50" x2="196.31575972509177" y2="-1.7037086855465873" stroke="url(#trail-1784477258927)" stroke-width="2" stroke-linecap="round">
                    <animate attributeName="x1" values="183.37480746996573;300.36101585630513" dur="10s" repeatCount="indefinite" begin="9.1s"/>
                    <animate attributeName="y1" values="-50;386.5984734826589" dur="10s" repeatCount="indefinite" begin="9.1s"/>
                    <animate attributeName="x2" values="196.31575972509177;313.30196811143117" dur="10s" repeatCount="indefinite" begin="9.1s"/>
                    <animate attributeName="y2" values="-1.7037086855465873;434.8947647971123" dur="10s" repeatCount="indefinite" begin="9.1s"/>
                </line>
                <image href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9ImN1cnJlbnRDb2xvciIgZD0iTTIxLjI1NCAxOC40Mkw5Ljc0NiAyMy45NDhhLjUuNSAwIDAgMS0uMjMuMDUzYS41NS41NSAwIDAgMS0uMjg0LS4wOGEuNTMuNTMgMCAwIDEtLjI0Ny0uNDV2LTUuNDc0bC02LjIxNy0yLjYwMmEuNTMuNTMgMCAwIDEtLjMyNy0uNDlWLjUzMWMwLS4xODEuMDkzLS4zNTQuMjQ4LS40NUEuNTQuNTQgMCAwIDEgMy4yMDIuMDVsMTEuOTY0IDUuNzQzbDUuNjMyLTIuNzAzYS41My41MyAwIDAgMSAuNTEzLjAzYS41My41MyAwIDAgMSAuMjQ4LjQ1MnYxNC4zN2EuNTQuNTQgMCAwIDEtLjMwNS40NzlNMy41MDMgMS4zNzhWMTQuNTVsNS40ODIgMi4yOTdWMTQuMmwtMy40NDctMS4zOWEuNTM3LjUzNyAwIDAgMS0uMjk2LS42OWEuNTMzLjUzMyAwIDAgMSAuNjktLjI5NmwzLjA1MyAxLjIzVjEwLjg4TDUuNTM4IDkuNDkyYS41MzcuNTM3IDAgMCAxLS4yOTYtLjY5YS41MzQuNTM0IDAgMCAxIC42OS0uMjk3bDMuMDUzIDEuMjN2LS42MzJjMC0uMjA0LjExNS0uMzkuMy0uNDc4bC43ODgtLjM4bC00LjU2Mi0yLjA3NmEuNTM0LjUzNCAwIDAgMS0uMjY1LS43MDNhLjUzNi41MzYgMCAwIDEgLjcwNC0uMjY2bDUuMzY3IDIuNDQ3TDEzLjkzIDYuMzl6bTE2Ljk5IDMuMDRMMTAuMDQ3IDkuNDM1djEzLjE5M2wxMC40NDYtNS4wMjJ6bS04LjQ1IDYuODY3bDUuOTg1LTIuODk0YS41My41MyAwIDAgMSAuNzA4LjI0OGEuNTI3LjUyNyAwIDAgMS0uMjQ3LjcwOGwtNS45ODcgMi44OTRhLjU1LjU1IDAgMCAxLS4yMy4wNTNhLjUzLjUzIDAgMCAxLS4yMy0xLjAxbTAgMy4zMThsNS45ODUtMi44OTNhLjUzLjUzIDAgMCAxIC43MDguMjQ4YS41MjcuNTI3IDAgMCAxLS4yNDcuNzA3bC01Ljk4NyAyLjg5NGEuNTUuNTUgMCAwIDEtLjIzLjA1M2EuNTMuNTMgMCAwIDEtLjIzLTEuMDA5bTAgMy4zMTRsNS45ODUtMi44OTNhLjUzLjUzIDAgMCAxIC43MDguMjQ3YS41MjcuNTI3IDAgMCAxLS4yNDcuNzA4TDEyLjUgMTguODcyYS41NS41NSAwIDAgMS0uMjMuMDUzYS41My41MyAwIDAgMS0uMjMtMS4wMDkiLz48L3N2Zz4=" width="32" height="32" x="180.31575972509177" y="-17.703708685546587" >
                    <animate attributeName="x" values="180.31575972509177;297.30196811143117" dur="10s" repeatCount="indefinite" begin="9.1s"/>
                    <animate attributeName="y" values="-17.703708685546587;418.8947647971123" dur="10s" repeatCount="indefinite" begin="9.1s"/>
                </image>
                <set attributeName="visibility" to="visible" begin="9.1s"/>
            </g>

    <image
            href="data:image/png;base64,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
