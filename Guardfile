guard :rspec, :keep_failed => false do
  watch(%r{^spec/.+_spec\.rb$})
  watch(%r{^(lib/.+)\.rb$})     { |m| "spec/#{m[1]}_spec.rb" }
  watch('spec/spec_helper.rb')  { "spec" }
end
