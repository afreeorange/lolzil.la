[lolzil.la](https://lolzil.la/)
===============================

🤷‍♂️ Will do something with this soon.

```bash
aws s3 sync --size-only --exclude "*.git*" . s3://lolzil.la/
```

TODO
----

* Use `sharp` for thumbnails
    - [Resize Docs](https://sharp.pixelplumbing.com/api-resize)
    - GIFs?
    - Videos?
* See [this near-complete example](https://docs.aws.amazon.com/lambda/latest/dg/with-s3-example.html) of how to do this with Node + Sharp, S3, and Lambda
