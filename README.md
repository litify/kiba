**If you need help**, please [ask your question with tag kiba-etl on StackOverflow](http://stackoverflow.com/questions/ask?tags=kiba-etl) so that other can benefit from your contribution! I monitor this specific tag and will reply to you.

Writing reliable, concise, well-tested & maintainable data-processing code is tricky.

Kiba lets you define and run such high-quality ETL ([Extract-Transform-Load](http://en.wikipedia.org/wiki/Extract,_transform,_load)) jobs using Ruby.

Learn more on the [Wiki](https://github.com/thbar/kiba/wiki), on my [blog](http://thibautbarrere.com) and on [StackOverflow](http://stackoverflow.com/questions/tagged/kiba-etl).

[![Gem Version](https://badge.fury.io/rb/kiba.svg)](http://badge.fury.io/rb/kiba)
[![Build Status](https://travis-ci.org/thbar/kiba.svg?branch=master)](https://travis-ci.org/thbar/kiba) [![Build status](https://ci.appveyor.com/api/projects/status/v05jcyhpp1mueq9i?svg=true)](https://ci.appveyor.com/project/thbar/kiba) [![Code Climate](https://codeclimate.com/github/thbar/kiba/badges/gpa.svg)](https://codeclimate.com/github/thbar/kiba) [![Dependency Status](https://gemnasium.com/thbar/kiba.svg)](https://gemnasium.com/thbar/kiba)

## Note on Kiba 2

Kiba 2 (not yet released) will include an improved engine. See #41 for the benefits and #42 for the WIP implementation.

## Getting Started

* [How do you define ETL jobs with Kiba?](https://github.com/thbar/kiba/wiki/How-do-you-define-ETL-jobs-with-Kiba%3F)
* [How do you run your ETL jobs?](https://github.com/thbar/kiba/wiki/How-do-you-run-your-ETL-jobs%3F)
* [Implementing ETL sources](https://github.com/thbar/kiba/wiki/Implementing-ETL-sources).
* [Implementing ETL transforms](https://github.com/thbar/kiba/wiki/Implementing-ETL-transforms).
* [Implementing ETL destinations](https://github.com/thbar/kiba/wiki/Implementing-ETL-destinations).
* [Implementing pre and post-processors](https://github.com/thbar/kiba/wiki/Implementing-pre-and-post-processors).

## Useful links

* [Live Coding Session - Processing data with Kiba ETL](http://thibautbarrere.com/2015/11/09/video-processing-data-with-kiba-etl/)
* [Rubyists - are you doing ETL unknowningly?](http://thibautbarrere.com/2015/03/25/rubyists-are-you-doing-etl-unknowingly/)
* [How to write solid data processing code](http://thibautbarrere.com/2015/04/05/how-to-write-solid-data-processing-code/)
* [How to reformat CSV files with Kiba](http://thibautbarrere.com/2015/06/04/how-to-reformat-csv-files-with-kiba/) (in-depth, hands-on tutorial)
* [How to explode multivalued attributes with Kiba ETL?](http://thibautbarrere.com/2015/06/25/how-to-explode-multivalued-attributes-with-kiba/)
* [Common techniques to compute aggregates with Kiba](https://stackoverflow.com/questions/31145715/how-to-do-a-aggregation-transformation-in-a-kiba-etl-script-kiba-gem)
* [How to run Kiba in a Rails environment?](http://thibautbarrere.com/2015/09/26/how-to-run-kiba-in-a-rails-environment/)
* [How to pass parameters to the Kiba command line?](http://stackoverflow.com/questions/32959692/how-to-pass-parameters-into-your-etl-job)

## Supported Ruby versions

Kiba currently supports Ruby 2.0+ and JRuby (with its default 1.9 syntax). See [test matrix](https://travis-ci.org/thbar/kiba).

## Kiba Common

I'm starting to add commonly used reusable helpers in a separate gem called [kiba-common](https://github.com/thbar/kiba-common), check it out (work-in-progress).

## ETL consulting & commercial version

**Consulting services**: if your organization needs help to implement a data pipeline or to build a data-intensive application, I provide consulting services. [More information](http://thibautbarrere.com/hire-me/).

**Kiba Pro**: for more features & goodies, check out Kiba Pro ([Changelog & contact info](Pro-Changes.md)).

## License

Copyright (c) LoGeek SARL. Kiba is an Open Source project licensed under the terms of
the LGPLv3 license.  Please see <http://www.gnu.org/licenses/lgpl-3.0.html> for license text.

## Contributing & Legal

(agreement below borrowed from [Sidekiq Legal](https://github.com/mperham/sidekiq/blob/master/Contributing.md))

By submitting a Pull Request, you disavow any rights or claims to any changes submitted to the Kiba project and assign the copyright of those changes to LoGeek SARL.

If you cannot or do not want to reassign those rights (your employment contract for your employer may not allow this), you should not submit a PR. Open an issue and someone else can do the work.

This is a legal way of saying "If you submit a PR to us, that code becomes ours". 99.9% of the time that's what you intend anyways; we hope it doesn't scare you away from contributing.
