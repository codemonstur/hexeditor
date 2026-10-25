# hexeditor

A Swing hex-viewer / hex-editor component recovered from the original
[fifesoft.com](https://fifesoft.com) HexEditor release. No more authoritative
source for the original project exists, so the sources are preserved here.

Pure Swing, no external dependencies.

## Components

Package `org.fife.ui.hex`:

| Class | Purpose |
| --- | --- |
| `swing.HexEditor` | The main drop-in hex editor component. |
| `swing.HexTable` / `HexTableModel` | The grid of bytes and its table model. |
| `swing.HexEditorRowHeader` | Row offset header column. |
| `swing.HexEditorTransferHandler` | Copy/paste and drag-and-drop support. |
| `swing.ByteArrayTransferable` | `Transferable` for raw byte arrays. |
| `ByteBuffer` | The underlying byte data model. |
| `event.HexEditorEvent` / `HexEditorListener` | Change notifications. |

## Dependency

```xml
<dependency>
  <groupId>com.github.codemonstur</groupId>
  <artifactId>hexeditor</artifactId>
  <version>0.1</version>
</dependency>
```

## Building

```sh
make build
```

## License

BSD 3-clause — original copyright belongs to **Robert Futrell**. This repository
only preserves the recovered source.
