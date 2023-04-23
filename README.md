# Full-Stack-Bootcamp-Notes
Welcome to my Full-Stack Bootcamp Notes repository! Here, you will find most of the code I wrote for homeworks and my personal notes throughout the bootcamp process using Java, HTML/CSS/JS, Angular, Springboot and PostgresSQL.


![Example image](https://s3.amazonaws.com/ae-lane-report/wp-content/uploads/2019/07/01105904/generalassembly-open-graph-300x158.jpg)

## Table of Contents
Technologies Used
How to Use
Code Examples
Contributing
License



## Technologies Used
During the Full-Stack Bootcamp, I had the opportunity to work with the following technologies:

Java
HTML/CSS/JS
Angular
Springboot
PostgresSQL


## How to Use
To access the code and notes in this repository, simply navigate to the corresponding folder and click on the file you wish to view. Feel free to clone this repository to your local machine if you want to run the code or make any changes

# Code Examples

```
// A Java class for a Person object
public class Person {
    private String name;
    private int age;

    public Person(String name, int age) {
        this.name = name;
        this.age = age;
    }

    public String getName() {
        return name;
    }

    public int getAge() {
        return age;
    }

    public void setName(String name) {
        this.name = name;
    }

    public void setAge(int age) {
        this.age = age;
    }
}
```

```
<!-- An HTML form for user input -->
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name"><br><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>
  <input type="submit" value="Submit">
</form>
```

```
// An Angular service for fetching data from an API
@Injectable({
  providedIn: 'root'
})
export class DataService {
  private apiUrl = 'https://api.example.com/data';

  constructor(private http: HttpClient) { }

  getData(): Observable<Data[]> {
    return this.http.get<Data[]>(this.apiUrl);
  }
}
```


## Contributing
If you find any errors or have any suggestions for improving the code or notes in this repository, feel free to open an issue or submit a pull request.

## License
This repository is licensed under the MIT License. See the LICENSE file for details.





