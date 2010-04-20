require 'rubygems'
require 'hoe'

$: << 'lib'
require 'audioinfo'

hoe = Hoe.new('ruby-audioinfo', AudioInfo::VERSION) do |p|
  p.rubyforge_name = 'ruby-audioinfo'
  p.author = 'Guillaume Pierronnet'
  p.email = 'moumar@rubyforge.org'
  p.extra_deps << [ "ruby-mp3info", ">= 0.6.3"]
  p.extra_deps << [ "ruby-ogginfo", ">= 0.3.1" ]
  p.extra_deps << [ "mp4Info", ">= 1.7.3" ]
  p.extra_deps << [ "wmainfo-rb", ">= 0.5" ]
  p.extra_deps << "flacinfo-rb"
  p.description = p.paragraphs_of('README.txt', 3).first
  p.summary = "ruby-audioinfo glue together various audio ruby libraries and presents a single API to the developper. Currently, supported formats are: mp3, ogg, mpc, ape, wma, flac, aac, mp4, m4a."
  p.url = "http://ruby-audioinfo.rubyforge.org"
  p.changes = p.paragraphs_of('History.txt', 0..1).join("\n\n")
  p.remote_rdoc_dir = ''
end

#task :tag_svn do
#  svn_repo = "svn+ssh://rubyforge.org/var/svn/ruby-audioinfo"
#  sh "svn copy -m 'tagged version #{hoe.version}' #{svn_repo}/trunk #{svn_repo}/tags/REL-#{hoe.version}"
#end
