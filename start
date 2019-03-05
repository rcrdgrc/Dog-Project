class Dog

    def initialize(name, breed, age, bark, fav_foods)
        @name = name
        @breed = breed
        @age = age
        @bark = bark
        @favorite_foods = fav_foods
    end

    def name
        @name
    end
   
    def breed
        @breed
    end

    def age
        @age
    end

    def bark
       @bark
    end
    
    def fav_foods
        @favorite_foods
    end

    def age=(num)
        @age = num
    end

    def bark
        if @age > 3
            return @bark.upcase
        else
            return @bark.downcase
        end
    end

    def favorite_foods
        @favorite_foods
    end

    def favorite_food?(str)
        @favorite_foods.include?(str[0].upcase + str[1..-1].downcase)
    end

end
