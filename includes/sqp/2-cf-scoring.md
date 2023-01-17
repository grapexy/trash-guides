#### Custom Formats and scores

{! include-markdown "../../includes/cf/radarr-audio.md" !}

{! include-markdown "../../includes/cf/radarr-hdr-formats.md" !}

{! include-markdown "../../includes/cf/radarr-movie-versions-imaxe.md" !}

??? abstract "HQ Release Groups - [CLICK TO EXPAND]"
    | Custom Format                                                                                                       | Score                                                   | Trash ID                                             |
    | ------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | ---------------------------------------------------- |
    | [{{ radarr['cf']['remux-tier-01']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#remux-tier-01)           | {{ radarr['cf']['remux-tier-01']['trash_score'] }}      | {{ radarr['cf']['remux-tier-01']['trash_id'] }}      |
    | [{{ radarr['cf']['remux-tier-02']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#remux-tier-02)           | {{ radarr['cf']['remux-tier-02']['trash_score'] }}      | {{ radarr['cf']['remux-tier-02']['trash_id'] }}      |
    | [{{ radarr['cf']['uhd-bluray-tier-01']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#uhd-bluray-tier-01) | {{ radarr['cf']['uhd-bluray-tier-01']['trash_score'] }} | {{ radarr['cf']['uhd-bluray-tier-01']['trash_id'] }} |
    | [{{ radarr['cf']['uhd-bluray-tier-02']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#uhd-bluray-tier-02) | {{ radarr['cf']['uhd-bluray-tier-02']['trash_score'] }} | {{ radarr['cf']['uhd-bluray-tier-02']['trash_id'] }} |
    | [{{ radarr['cf']['uhd-bluray-tier-03']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#uhd-bluray-tier-03) | {{ radarr['cf']['uhd-bluray-tier-03']['trash_score'] }} | {{ radarr['cf']['uhd-bluray-tier-03']['trash_id'] }} |
    | [{{ radarr['cf']['web-tier-01']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#web-tier-01)               | {{ radarr['cf']['web-tier-01']['trash_score'] }}        | {{ radarr['cf']['web-tier-01']['trash_id'] }}        |
    | [{{ radarr['cf']['web-tier-02']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#web-tier-02)               | {{ radarr['cf']['web-tier-02']['trash_score'] }}        | {{ radarr['cf']['web-tier-02']['trash_id'] }}        |
    | [{{ radarr['cf']['web-tier-03']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#web-tier-03)               | {{ radarr['cf']['web-tier-03']['trash_score'] }}        | {{ radarr['cf']['web-tier-03']['trash_id'] }}        |

    !!! Danger "- Don’t use HQ-xxx or UHD (xxx) and Tiers together<br>- Remux Tier 01-02 replaces HQ-Remux<br>- UHD Bluray Tier 01-03 replaces UHD (xxx)<br>- Web Tier 01-03 replaces HQ-WEBDL"

{! include-markdown "../../includes/sqp/uhd-radarr-misc.md" !}

{! include-markdown "../../includes/sqp/uhd-radarr-unwanted.md" !}

{! include-markdown "../../includes/sqp/uhd-radarr-optional.md" !}

{! include-markdown "../../includes/sqp/uhd-radarr-resolution.md" !}

{! include-markdown "../../includes/cf/radarr-streaming-services.md" !}
