??? summary "Unwanted - [CLICK TO EXPAND]"
    | Custom Format                                                                                                       | Score                                                | Trash ID                                          |
    | ------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------- |
    | [{{ sonarr['cf']['br-disk']['name'] }}](/Sonarr/sonarr-collection-of-custom-formats/#br-disk)                       | {{ sonarr['cf']['br-disk']['trash_score'] }}         | {{ sonarr['cf']['br-disk']['trash_id'] }}         |
    | [{{ sonarr['cf']['french-lq']['name'] }}](/Sonarr/sonarr-collection-of-custom-formats/#fr-lq)                       | {{ sonarr['cf']['french-lq']['trash_score'] }}       | {{ sonarr['cf']['french-lq']['trash_id'] }}       |
    | [{{ sonarr['cf']['x265-hd']['name'] }}](/Sonarr/sonarr-collection-of-custom-formats/#x265-hd) :warning:             | {{ sonarr['cf']['x265-hd']['trash_score'] }}         | {{ sonarr['cf']['x265-hd']['trash_id'] }}         |

    ------

    Breakdown and Why

    - **{{ sonarr['cf']['br-disk']['name'] }} :** This is a custom format to help Sonarr recognize & ignore BR-DISK (ISO's and Blu-ray folder structure) in addition to the standard BR-DISK quality.
    - **{{ sonarr['cf']['french-lq']['name'] }}:** A collection of known Low Quality French groups that are often banned from the top trackers because the lack of quality or other reasons.
    - **{{ sonarr['cf']['x265-hd']['name'] }}:** This blocks 720/1080p (HD) releases that are encoded in x265. - More info [HERE](/Misc/x265-4k/){:target="_blank" rel="noopener noreferrer"}.

        !!! Danger "Don't use this together with [{{ sonarr['cf']['x265-no-hdrdv']['name'] }}](/Sonarr/sonarr-collection-of-custom-formats/#x265-no-hdrdv), Only ever include one of them :warning:"
