# This is for the testing
class Hello
   
   def initialize( name )
      @name = name.capitalize
   end

   def salute
      puts "Hello #{@name}!"
   end
   
end

# Create a new object
h = Hello.new("Ruby")

# Output "Hello Dan Mo!"
h.salute
