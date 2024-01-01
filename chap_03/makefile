NAME		=	avg

CC			=	clang++
INCLUDES	=	includes
CPPFLAGS	=	-Wall -Werror -Wextra -I$(INCLUDES)
RM			=	rm -rf

SRCS		=	avg.cpp

all:		$(NAME)

$(NAME):
			$(CC) $(CPPFLAGS) $(SRCS) -o $(NAME)

fclean:
			$(RM) $(NAME)

re:			fclean all

.PHONY:		fclean, all, re