def calculate_triangle_area(base, height):
    return 0.5 * base * height

# Example usage
base = float(input("Enter the base of the triangle: "))
height = float(input("Enter the height of the triangle: "))
area = calculate_triangle_area(base, height)
print(f"The area of the triangle is {area}")
