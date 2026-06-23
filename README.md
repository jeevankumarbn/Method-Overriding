class Shape:
    def draw(self):
        print("Drawing shape.")

class Circle(Shape):
    def draw(self):
        super().draw()
        print("Drawing Circle.")


c = Circle()
c.draw()
