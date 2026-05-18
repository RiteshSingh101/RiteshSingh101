/**
 * Ritesh Singh — Backend Engineer
 * Mumbai, India 🇮🇳
 *
 * I build robust, scalable Java backends that solve real problems.
 * Currently deep in System Design & Microservices Architecture.
 * Long-term goal: found a product-led startup in the B2B SaaS space.
 */
public class RiteshSingh implements BackendEngineer, StartupFounder {

    private final String       location       = "Mumbai, India";
    private final String       role           = "Java Backend Developer";
    private final String[]     currentlyDoing = {
        "Mastering System Design & Microservices",
        "Building production-grade Spring Boot APIs",
        "Sharpening DSA skills for competitive engineering"
    };
    private final String[]     techFocus      = {
        "Java 17+", "Spring Boot 3", "Hibernate 6",
        "MySQL", "REST APIs", "JDBC"
    };
    private final String       openTo         = "Internships • Freelance Projects • Open Source Collab";
    private final String       mission        = "Ship fast. Build right. Scale smart.";

    @Override
    public String getGoal() { return "Build a profitable startup by 2027"; }
}
