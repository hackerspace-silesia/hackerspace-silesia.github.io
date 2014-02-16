guard 'bundler' do
  watch('Gemfile')
end

guard 'sass', input: '_assets/stylesheets'
guard 'coffeescript', input: '_assets/javascripts'

guard 'jekyll-plus' do
  watch /.*/
  ignore /^_site/
end
