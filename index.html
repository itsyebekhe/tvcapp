<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SUBLINKS</title>
<!-- Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
<!-- Custom styles for dark theme -->
<link href="styles.css" rel="stylesheet" />
</head>
<body>

<div class="container my-5">
  <h1 class="text-center mb-4">SUBLINKS</h1>
  <div class="card">
    <div class="card-body">
  <form>
    <div class="mb-3">
      <label for="core" class="form-label">Select Core</label>
      <select class="form-select" id="core">
        <option value="">-- Select Core --</option>
        <option value="xray">XRAY</option>
        <option value="singbox">SING-BOX</option>
        <option value="clash">CLASH</option>
        <option value="meta">CLASH.Meta</option>
        <option value="surfboard">SURFBOARD</option>
      </select>
    </div>

    <div class="mb-3" id="option-container" style="display: none;">
      <select class="form-select" id="option">
        <!-- Options will be populated here -->
      </select>
    </div>

    <div class="mb-3" id="option-container-two" style="display: none;">
      <select class="form-select" id="option-xray">
        <!-- Options will be populated here -->
      </select>
    </div>

    <div class="mb-3 form-check">
      <input type="checkbox" class="form-check-input" id="lite">
      <label class="form-check-label" for="lite">Lite</label>
    </div>

    <button class="btn btn-primary" id="generate-btn">Generate URL</button>
  </form>

  <div class="form-group mt-4">
    <label for="output">Generated URL</label>
    <textarea class="form-control" id="output" rows="3" readonly></textarea>
    <button class="btn btn-primary mt-2" id="copy-btn">Copy URL</button>
    <button class="btn btn-primary mt-2" id="format-btn" onclick="formatAndOpenLink()">Import in Hiddify</button>
  </div>
</div>
</div>
</div>
<!-- Bootstrap Bundle with Popper -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
<script>
const optionsXray = ["PROTOCOLS", "COUNTRIES", "OPERATORS"];
const optionsXrayProtocol = ['MIX', 'VMESS', 'VLESS', 'REALITY', 'TROJAN', 'SS'];
const optionsXrayCountry = ["AE", "AT", "BH", "CA", "CF", "CH", "CN", "DE", "FI", "FR", "GB", "HK", "ID", "IE", "IL", "IN", "IR", "JP", "NL", "PL", "RU", "SE", "SG", "US", "XX"];
const optionsXrayOperators = ['MCI', 'MTN', 'MKH'];

const optionsSing = ['MIX', 'VMESS', 'VLESS', 'REALITY', 'TROJAN', 'SS', 'TUIC', 'HY2'];
const optionsSurf = ['MIX', 'VMESS', 'TROJAN', 'SS'];

function getCountryCodeEmoji(countryCode) {
    const countryCodeEmojis = {
        'AE': '🇦🇪',
        'AT': '🇦🇹',
        'BH': '🇧🇭',
        'CA': '🇨🇦',
        'CF': '🚩',
        'CH': '🇨🇭',
        'CN': '🇨🇳',
        'DE': '🇩🇪',
        'FI': '🇫🇮',
        'FR': '🇫🇷',
        'GB': '🇬🇧',
        'HK': '🇭🇰',
        'ID': '🇮🇩',
        'IE': '🇮🇪',
        'IL': '🇮🇱',
        'IN': '🇮🇳',
        'IR': '🇮🇷',
        'JP': '🇯🇵',
        'NL': '🇳🇱',
        'PL': '🇵🇱',
        'RU': '🇷🇺',
        'SE': '🇸🇪',
        'SG': '🇸🇬',
        'US': '🇺🇸',
        'XX': '🏳️' // Default emoji for unknown country codes
    };

    return countryCodeEmojis[countryCode.toUpperCase()] || countryCodeEmojis['XX'];
}
 
// Function to format the link and open it in a new tab
function formatAndOpenLink() {
    const core = document.getElementById('core').value;
    if (core != "surfboard") {
        var generatedLink = document.getElementById('output').value;
        if (!generatedLink) {
            alert('Please first Generate a URL.');
            return;
        }
        var formattedLink = 'hiddify://import/' + generatedLink;
        window.open(formattedLink, '_blank');
    } else {
      alert("Hiddify don't support surfboard URLs.");
      return;
    }
}
  
document.getElementById('core').addEventListener('change', function() {
  const core = this.value;
  const optionContainer = document.getElementById('option-container');
  const optionSelect = document.getElementById('option');
  const optionXrays = document.getElementById('option-xray');

  // Clear previous options
  optionSelect.innerHTML = '<option value="">-- Select --</option>';

  // Show option container only if a protocol is selected
  if (core) {
    optionContainer.style.display = 'block';
    if (core == "xray") {
      optionsXray.forEach((optionText, index) => {
        const option = document.createElement('option');
        option.value = optionText.toLowerCase();
        option.text = optionText;
        optionSelect.add(option);
      });
    } else if (core == "meta") {
      optionsXrayProtocol.forEach((optionText, index) => {
        const option = document.createElement('option');
        option.value = optionText.toLowerCase(); 
        option.text = optionText;
        optionSelect.add(option);
      });
    } else if (core == "singbox") {
      optionsSing.forEach((optionText, index) => {
        const option = document.createElement('option');
        option.value = optionText.toLowerCase(); 
        option.text = optionText;
        optionSelect.add(option);
      });
    } else if (core == "surfboard" || core == "clash") {
      optionsSurf.forEach((optionText, index) => {
        const option = document.createElement('option');
        option.value = optionText.toLowerCase(); 
        option.text = optionText;
        optionSelect.add(option);
      });
    }
  } else {
    optionContainer.style.display = 'none';
  }
});

document.getElementById('option').addEventListener('change', function() {
  const item = this.value;
  const core = document.getElementById('core').value;
  const optionContainerTwo = document.getElementById('option-container-two');
  const optionXrayType = document.getElementById('option-xray');
   // Clear previous options
   optionXrayType.innerHTML = '<option value="">-- Select --</option>';
  if (core == "xray" && item != "") {
    optionContainerTwo.style.display = 'block';
    if (item == "protocols") {
      optionsXrayProtocol.forEach((optionText, index) => {
        const option = document.createElement('option');
        option.value = optionText.toLowerCase(); 
        option.text = optionText;
        optionXrayType.add(option);
      });
    } else if (item == "countries") {
        optionsXrayCountry.forEach((optionText, index) => {
          const option = document.createElement('option');
          option.value = optionText.toLowerCase(); 
          option.text = getCountryCodeEmoji(optionText) + " " + optionText;
          optionXrayType.add(option);
        });
    } else if (item == "operators") {
        optionsXrayOperators.forEach((optionText, index) => {
          const option = document.createElement('option');
          option.value = optionText.toLowerCase(); 
          option.text = optionText;
          optionXrayType.add(option);
        });
    }
  } else {
    optionContainerTwo.style.display = 'none';
  }
});

document.getElementById('generate-btn').addEventListener('click', function(event) {
  event.preventDefault();
  const core = document.getElementById('core').value;
  const option = document.getElementById('option').value;
  const optionTwo = document.getElementById('option-xray').value;
  const lite = document.getElementById('lite').checked;

  if (!core || !option) {
    alert('Please select a core and a protocol.');
    return;
  }

  if (core == "xray" && !optionTwo) {
    alert('Please select all selectors.');
    return;
  }

  let baseUrl;
  if (lite) {
    if (core == "xray") {
        if (option == "protocols") {
            baseUrl = `https://raw.githubusercontent.com/yebekhe/TVC/main/lite/subscriptions/xray/base64/`;
        } else if (option == "countries") {
            baseUrl = `https://raw.githubusercontent.com/yebekhe/TVC/main/lite/subscriptions/location/base64/`;
        } else if (option == "operators") {
            baseUrl = `https://api.yebekhe.link/tested-config/?base64=true&operator=`;
        }
    } else {
        baseUrl = `https://raw.githubusercontent.com/yebekhe/TVC/main/lite/subscriptions/${core}/`;
    }
  } else {
    if (core == "xray") {
        if (option == "protocols") {
            baseUrl = `https://raw.githubusercontent.com/yebekhe/TVC/main/subscriptions/xray/base64/`;
        } else if (option == "countries") {
            baseUrl = `https://raw.githubusercontent.com/yebekhe/TVC/main/subscriptions/location/base64/`;
        } else if (option == "operators") {
            baseUrl = `https://api.yebekhe.link/tested-config/?base64=true&operator=`;
        }
    } else {
        baseUrl = `https://raw.githubusercontent.com/yebekhe/TVC/main/subscriptions/${core}/`;
    }
  }
let fullUrl;
  if (core == "xray") {
    if (option == "countries") {
        fullUrl = baseUrl + optionTwo.toUpperCase();
    } else {
        fullUrl = baseUrl + optionTwo;
    }
  } else if (core == "singbox") {
    fullUrl = baseUrl + option + ".json";
  } else {
    fullUrl = baseUrl + option;
  }
  document.getElementById('output').value = fullUrl;
});

document.getElementById('copy-btn').addEventListener('click', function() {
  const output = document.getElementById('output');
  output.select();
  document.execCommand('copy');
  alert('URL copied to clipboard');
});
</script>

</body>
</html>
