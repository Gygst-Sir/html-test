<!DOCTYPE html>
<html>
<head>
  <title>Welcome</title>
 
</head>
<body>
 
    <h1>\{{ greeting }}</h1>
    <ul>
      <li>
        To learn more about Vue, visit
        <a :href="docsURL" target="_blank">
          \{{ humanizeURL(docsURL) }}
        </a>
      </li>
      <li>
        For live help with simple questions, check out
        <a :href="discordURL" target="_blank">
          Discord?
        </a>
      </li>
      <li>
        For more complex questions, post to
        <a :href="forumURL" target="_blank">
          the forum
        </a>
      </li>
    </ul>
  </div>

  <script>
    var app = new Vue({
      el: '#app',
      data: {
       
        }
      }
    })
  </script>
</body>
</html>
