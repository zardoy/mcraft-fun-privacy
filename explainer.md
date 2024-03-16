# Mcraft.fun Scopes explainer

- `https://www.googleapis.com/auth/drive` - required for full read-write access for user's Google Drive storage. User can specify an arbitrary path that app will use to read and write files. This is the essential feature of the app as it allows to access worlds from different existing directories. The app **will not have access** to any other files outside of the specified path. The app will not have access to any other Google services. By default app operate in read-only mode, user can enable write access by toggling "Read Only" button in the app.
