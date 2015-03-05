# <%=humanize(context['package.name'])%>

<%=context['package.description']%>

<%if(context['readme.doodle']){%>![doodle](<%=context['readme.doodle']%>)
<%}%><%if(context['readme.content']){%><%=context['readme.content']%>
<%}%>
