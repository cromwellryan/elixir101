# A sample Guardfile
# More info at https://github.com/guard/guard#readme

# Add files and commands to this file, like the example:
#   watch(%r{file/path}) { `command(s)` }
#
guard 'shell' do
  watch(/(.*).exs/) {|m| `mix run #{m[0]}` }
end

guard 'shell' do
  watch(/(.+\.ex$)/) { |m| `mix run #{m[0]}` }
end
