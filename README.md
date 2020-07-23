# pr0vidownr

Diese Anwendung ermöglicht das Herunterladen von Videos der Seite pr0gramm.com.

## Bookmarklet

[Als Lesezeichen speichern](javascript:var id=/[^/]*$/.exec(window.location.href)[0];var url=`https://pr0vidownr.herokuapp.com/?id=${id}`;window.location.href = url;)
