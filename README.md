public class AshikaM
{
    private string name = "Ashika M";
    private string location = "Tamil Nadu, India";
    private string degree = "B.E. Computer Science & Engineering";

    private string[] stack = {
        "C#", "ASP.NET Core", "ASP.NET MVC", "SignalR",
        "Entity Framework Core", "ADO.NET", "SQL Server",
        "MySQL", "PostgreSQL", "ReactJS", "JavaScript", "Flask"
    };

    private string[] currentlyLearning = {
        "Advanced System Design", "Cloud (Azure)", "Microservices"
    };

    private string funFact =
        "Replaced Entity Framework with hand-rolled ADO.NET " +
        "+ stored procedures to squeeze out performance on a " +
        "hospital ERP handling large transactional data.";

    public string motto() =>
        "Clean architecture today saves debugging tomorrow.";
}
