import android.os.Bundle;
import androidx.appcompat.app.AppCompatActivity;
import com.jterm.terminalview.TerminalView;

public class MainActivity extends AppCompatActivity {

    private TerminalView terminalView;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        terminalView = findViewById(R.id.terminal_view);
        terminalView.setTerminalListener(new TerminalView.TerminalListener() {
            @Override
            public void onCommandExecuted(String command, String output) {
                // Handle command output here
            }
        });

        // Example command
        terminalView.executeCommand("echo Hello, Terminal!");
    }
}
