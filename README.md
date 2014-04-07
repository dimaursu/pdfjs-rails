# Pdfjs::Rails

TODO: Write a gem description

## Installation

Add this line to your application's Gemfile:

    gem 'pdfjs-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install pdfjs-rails

## Usage

After bundling, add in application.js 

    //= require pdfviewer
    
and in aplication.css 

    *= require viewer

In a view you can call the following, assuming @course.slides contains the path to the PDF file.

    = pdf_viewer @course.slides


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
