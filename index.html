 import com.sun.net.httpserver.HttpServer;
import java.net.InetSocketAddress;
import java.nio.file.Files;
import java.nio.file.Path;

public class WardApp {

    public static void main(String[] args) throws Exception {

        HttpServer server = HttpServer.create(
            new InetSocketAddress(8080), 0
        );

        server.createContext("/", exchange -> {

            byte[] page = Files.readAllBytes(
                Path.of("index.html")
            );

            exchange.getResponseHeaders()
                .set("Content-Type", "text/html; charset=UTF-8");

            exchange.sendResponseHeaders(200, page.length);

            exchange.getResponseBody().write(page);
            exchange.getResponseBody().close();
        });

        server.start();

        System.out.println("Ward App is running!");
        System.out.println("Open: http://localhost:8080");
    }
}