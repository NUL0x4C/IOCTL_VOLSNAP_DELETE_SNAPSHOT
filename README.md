## Querying And Deleting Shadow Copies Using The [IOCTL_VOLSNAP_QUERY_NAMES_OF_SNAPSHOTS](https://github.com/NUL0x4C/IOCTL_VOLSNAP_DELETE_SNAPSHOT/blob/IOCTL_VOLSNAP_QUERY_NAMES_OF_SNAPSHOTS/QueryAndDeleteSnapshotsViaIOCTL/Main.c#L10) & [IOCTL_VOLSNAP_DELETE_SNAPSHOT](https://github.com/NUL0x4C/IOCTL_VOLSNAP_DELETE_SNAPSHOT/blob/IOCTL_VOLSNAP_QUERY_NAMES_OF_SNAPSHOTS/QueryAndDeleteSnapshotsViaIOCTL/Main.c#L19) IOCTLs


</br>

> [!NOTE]
> **This branch completely avoids using any COM/VSS API, and instead, completely relies on IOCTL codes to query and delete all existing Shadow Copies**



</br>


<img width="1231" height="344" alt="image" src="https://github.com/user-attachments/assets/c0726eb5-13c2-490d-a54e-6e2cc0824889" />



</br>

### This repository is inspired by [gtworek/IOCTL_VOLSNAP_SET_MAX_DIFF_AREA_SIZE](https://github.com/gtworek/PSBits/tree/master/IOCTL_VOLSNAP_SET_MAX_DIFF_AREA_SIZE)
