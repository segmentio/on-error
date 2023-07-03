
# on-error

> **Note**  
> Segment has paused maintenance on this project, but may return it to an active status in the future. Issues and pull requests from external contributors are not being considered, although internal contributions may appear from time to time. The project remains available under its open source license for anyone to use.

  Safely attach a handler to `window.onerror` regardless of existing handlers. 

  It will also rebind to `window.onerror` if another party clobbers it.

## Installation

    $ component install segmentio/on-error

## API

### onError(fn)
  Call `fn` when an error is thrown on the page.

## License

  MIT
